The goal of this project is to be used as a tool in CICD pipelines offering a CLI tool that can build any type of LabVIEW applications after ingesting a .ini file with the build configuration.

Project milestones:

- [X] build a package library by providing settings that are usually inputed manually in the "build specification" section of a LabVIEW project
- [ ] handle externals referencing
- [ ] wrap the builder in a state machine and launch it async collecting output result
- [ ] embbed the state machine into a CLI app that can return build status and error logs
- [ ] expand functionality to support .exe
- [ ] expand functionality to support .nipkg
- [ ] explore the possibility of multiple simultaneous builds or sequential builds and automation with build scripts
- [ ] add support for static code analysis via a custom VI Analyzer script
- [ ] add support static code analysis via customized pre and post build actions
- [ ] add support for unity testing using Caraya test framework