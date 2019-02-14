# Registrator

![](julia_id.jpg)

Contributions are welcome: [Registrator.jl](https://github.com/JuliaComputing/Registrator.jl)

Click [here](https://github.com/apps/registratortest/installations/new) to install.

#### How to use

Raise an issue in the package you wish to register. Add `register()` somewhere in the content of the issue if you are a collaborator to trigger Registrator. If you are not a collaborator ask someone who is to comment `register()` on the issue. This will make Registrator add a pull request to General with the appropriate changes. Registrator will look for the project file in the master branch by default. To use a custom branch comment with `register(name-of-your-branch)`.

Alternatively, create a pull request on the package repo with your project file changes. As above, add `register()` as the content body of the pull request or as a comment (or ask a collaborator). This will make Registrator add a pull request to General by looking at your pull request branch.
