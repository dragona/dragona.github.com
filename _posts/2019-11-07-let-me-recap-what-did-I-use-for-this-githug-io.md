---
title: My steps into building this IO page 
---

- Creating the repository:
    - name the new repos ```github_account_name.io``` 
    - add a theme to the repos from the ```settings``` tab in github 
- Using a bootstrap theme
    - Clone the Bootstrap 4 for Github on your local machine
    - Clone your newly created repository
    - By default, there should be two files in your cloned repository (not including the hidden files), remove them then drag and drop the content
    of the cloned project Bootstrap 4 for Github onto your repository
    - ```git add -A```, ```git commit -m "first commit"``` then push the update to your GitHub account
    
You may need to wait before the changes take effect when you visit your .io page. In the meantime, my next step was to change the theme.

- Changing theme:
    - Choose a theme from [Bootswatch](https://bootswatch.com/)
    - Download the ```_variable.scss``` and the ```_bootswatch.scss```
    - Under you ```_sass``` project folder, open the file ```_bootstrap_customization.scss``` and replace its content with what you have in the ```_bootswatch.scss``` newly downloaded.
     Do the same for the ```_variable.scss``` already in your project folder and the one you just downloaded
    - ```git add -A```, ```git commit -m "Css update"``` then push the update to your GitHub account
    
- Adding the posts
    - Create a folder ```_posts``` in the root directory of your project.
    - For each post, create a new ```.md``` file. The file name should not contain any space. You can use ```-``` instead.
    - Open the ```index.md``` file and update the header part where you have
        ```
        layout: page
        ``` 

        and replace it with 
        ```
        layout: home
        ```
    - ```git add -A```, ```git commit -m "Add post"``` then push the update to your GitHub account
      
      
That was it!