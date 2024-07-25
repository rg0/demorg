# Configure push mirroring

To set up push mirroring for an existing project:

    On the left sidebar, select Search or go to and find your project.
    Select Settings > Repository.
    Expand Mirroring repositories.
    Enter a repository URL.
    In the Mirror direction dropdown list, select Push.
    Select an Authentication method.

 Create a PAT from GitHub:

    Click on your GitHub profile icon on the top right corner
    Click Settings
    From the menu shown on the left, click Developer Settings
    Click Personal access tokens
https://github.com/settings/tokens
    Click Generate new token
    Add a note that will help you identify the scope of the access token to be generated
    Choose the Expiration period from the drop down menu (Ideally you should avoid choosing the No Expiration option)
    Finally, select the scopes you want to grant the corresponding access to the generated access token. Make sure to select the minimum required scopes otherwise you will still have troubles performing certain Git Operations.
    Finally click Generate Token.


From GitLab, Go to repo you wish to mirror:

    Click on Settings.
    Click on Repository.
    Click on Mirror Repo option --> Expand it.
Select Push
Add repo url.git
user pass

-----------------
    Use below url for Git repository URL: https://<<githubtoken>>@github.com/<<username>>/<<repositoryname>>.git
    Use the token created in Step 1 to use in the part in URL above.
    Click on Mirror Repository button without filling the password field.





