Building an IO Page:

Creating the repository:
a. Name the new repo "github_account_name.io"
b. Add a theme in the Github "settings" tab.
Using a Bootstrap theme:
a. Clone Bootstrap 4 for Github to your local machine.
b. Clone your newly created repo and remove the default two files.
c. Drag and drop the content of the cloned Bootstrap 4 project to your repo.
d. Run "git add -A", "git commit -m 'first commit'" and push to your Github account.
Note: Wait for changes to take effect when visiting the .io page.

Changing theme:
a. Choose a theme from Bootswatch.
b. Download the "_variable.scss" and "_bootswatch.scss" files.
c. Replace the content in "_bootstrap_customization.scss" and "_variable.scss" with the newly downloaded files.
d. Run "git add -A", "git commit -m 'CSS update'" and push to your Github account.

Adding posts:
a. Create a "_posts" folder in the root directory.
b. Create a new ".md" file for each post with a name without spaces (use "-").
c. Update the header in "index.md" from "layout: page" to "layout: home".
d. Run "git add -A", "git commit -m 'Add post'" and push to your Github account.

That's it!"