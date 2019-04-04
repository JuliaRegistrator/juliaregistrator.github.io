#### Usage

Registration is triggered on github by mentioning the bot by name using the markdown "``` @JuliaRegistrator `$command` ```" with the appropriate `$command`. The bot must first be **installed on your repository** for this to work.

The bot will only respond to new comments coming **from maintainers or collaborators**. If you're not a collaborator you will need to ask a maintainer or collaborator to trigger registration for you.

The bot listens for comments on both GitHub issues and commits so you can either:

* **Raise a GitHub issue** and add "@JuliaRegistrator `register()`" somewhere in the content of the issue. Alternatively a collaborator can do this for you by adding a new comment to the issue. Registrator will use the project file in the master branch by default but you can use a custom release branch with the command `register(name-of-your-branch)`.
* Alternatively, **click on particular a GitHub commit** and write "@JuliaRegistrator `register()`" in the comment section. Note that you must be a collaborator in order to do this.

Registrator will then create a pull request to the General registry using the version information in the project file on your branch or commit.
