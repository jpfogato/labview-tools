The goal of this project is to be used as a tool in CICD pipelines offering a CLI tool that can build any type of LabVIEW applications after ingesting a .ini file with the build configuration.

Project milestones:

- [X] build a package library by providing settings that are usually inputed manually in the "build specification" section of a LabVIEW project
- [X] preapre the CLI option capabilities and document a "-h/--help" option call
- [ ] embedd the builder into a CLI app that can return result, build statuses and eventual error messages
- [ ] expand functionality to support .exe
- [ ] expand functionality to support .nipkg
- [ ] explore the possibility of multiple simultaneous builds or sequential builds and automation with build scripts
- [ ] add support for static code analysis via a custom VI Analyzer script
- [ ] add support code quality checks via customized pre and post build actions
	- [ ] disable debug, error handling, set execution thread, etc.
- [ ] add support for unity testing using Caraya test framework with pre-build actions