# Building an IO Page

## Creating the repository:
1. Name the new repo "github_account_name.io"
2. Add a theme in the Github "settings" tab.

## Using a Bootstrap theme:
1. Clone Bootstrap 4 for Github to your local machine.
2. Clone your newly created repo and remove the default two files.
3. Drag and drop the content of the cloned Bootstrap 4 project to your repo.
4. Run the following Git commands:
    ```
    git add -A
    git commit -m 'first commit'
    git push
    ```

Note: Wait for changes to take effect when visiting the .io page.

## Changing theme:
1. Choose a theme from Bootswatch.
2. Download the "_variable.scss" and "_bootswatch.scss" files.
3. Replace the content in "_bootstrap_customization.scss" and "_variable.scss" with the newly downloaded files.
4. Run the following Git commands:
    ```
    git add -A
    git commit -m 'CSS update'
    git push
    ```

## Adding posts:
1. Create a "_posts" folder in the root directory.
2. Create a new ".md" file for each post with a name without spaces (use "-").
3. Update the header in "index.md" from "layout: page" to "layout: home".
4. Run the following Git commands:
    ```
    git add -A
    git commit -m 'Add post'
    git push
    ```

That's it!
