# Sample Doctrinis Training Module

## Customizing
Documentation pending...
## Building
To build the module to a Windows Application (EXE) you can use the following command from the root of the project source:
`docker run -v ${PWD}:/project ghcr.io/doctrinis/doctrinis`
(this requires docker is installed on your system)

## Alternate workflow:
Simply fork this project, rename it as you'd like, make customizations, and then commit the changes back. Github Actions will auto build the application. Once ready (it builds with no errors) you can tag it with a semver release (ie: v1.0.0) and push the tag to github, this will result in github automatically creating a release with a matching version number, and the built EXE file will be stored in that release for download.