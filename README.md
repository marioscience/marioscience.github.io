# marioscience.github.io
Resume and portfolio.

Please visit my [portfolio and resume](https://mariomatos.dev/)

There is a ```resume.json``` file with the specification file for my resume. This uses the standard for json resumes found at https://jsonresume.org/

### Generate resume files

To generate a resume using a different theme, make sure to clone the theme github in the project's root directory and run ```resume export index.html --format html --theme <theme-name>```. This requires ```resume-cli``` to be installed, install dependencies as needed. 
An ```index.html``` will be created which, at the moment, I am hosting using github pages. This requires the ```index.html``` to be pushed to the repository named ```marioscience.github.io``` under my github account.
  
### Manual Changes to index.html

Here I want to keep track of manual changes that I have done to the index.html. Since the theme is auto-generated tweaking the theme requires either manual changes to the ```index.html``` or forking the theme and making the changes in the theme itself. This last one would be more maintainable but requires a learning curve, trade-offs, trade-offs, what to do about trade-offs... for now I am making the changes manually and keeping track here. 

- Removed spacing in list items for work experience. Just set their margin to zero for the ```<p>``` element in the CSS.
- Added Google Analytics in ```<head>```, for details go to Google Analytics dashboard.
- Some hyphens for the dates have space in their right side and not on the left, i.e. Nov 2016- Dec 2020 and it looks a bit ugly. So I added spaces for them i.e. Nov 2016 - Dec 2020.
  
For more info on these changes check out the commit history for the ```index.html``` file. 

### Hosting

At the moment https://mariomatos.dev/ is a domain name that directly redirects to https://marioscience.github.io/. This is a DNS redirect with masking.
