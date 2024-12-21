# Basic portofolio for Submission Proyek Deploy Aplikasi Profile 

# Kelas Menjadi Google Cloud Engineer - Dicoding

- Deploy Static Web App in Google App Engine

## Basic structure for the project :
- app.yaml: Configure the settings of your App Engine application.
- www/: Directory to store all of your static files, such as HTML, CSS, images, and JavaScript.
  - css/: Directory to store stylesheets.
    - style.css: Basic stylesheet that formats the look and feel of your site.
  - images/: Optional directory to store images.
  - index.html: An HTML file that displays content for your website.
  - js/: Optional directory to store JavaScript files.
  - Other asset directories.
 
## Description
1. ```app.yaml```: Configure the settings of your App Engine application.
2. ```www/```: Directory to store all of your static files, such as HTML, CSS, images, and JavaScript.
3. ```css/```: Directory to store stylesheets.
4. ```style.css```: Basic stylesheet that formats the look and feel of your site.
5. ```img/```: Optional directory to store images.
6. ```index.html```: An HTML file that displays content for your website.
7. ```js/```: Optional directory to store JavaScript files.
8. Other asset directories.

## Step-by-step
1. Configure the ```app.yaml```
2. Create app engine
3. Clone the website repo to code editor
4. Use command in Cloud Console with the dir ```gcloud app deploy```
5. Viewing your application using command ```gcloud app browse```

- My Website
![My Website](Documentation/web-display.png)
- Rating Submission
![Rating](Documentation/Rating.png)

- Full Reference : https://cloud.google.com/appengine/docs/standard/hosting-a-static-website
