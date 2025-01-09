# Lua Validation Toolkit
Tools to create validation specs for lua projects.

## NOTE: THIS REPO IS IN IT'S INFANCY STAGE, EVERYTHING IS SUBJECT TO RADICAL CHANGE INCLUDING THE PROJECT NAME AND GOALS

## Inspiration
Partly general insatisfaction with no proper validators for code against versions of
libraries. Luacheck does a good job but it lacks definitions. The lack of a common
standard for definition files doesn't help. Also every project/coder annotates
differently or not at all. The secondary benifit of this project is limited in supporting
code completion definitions because of missing annotations. The results from these tools
can provide some sort of middle ground where at least the editors can know of existing
methods and global variables.

## Goals (all up to some point):
- [ ] basic converter `.luacheckrc` to `.luarc.json`.
- [ ] generate portable scheme files of code base.
- [ ] support [luacheck](https://github.com/lunarmodules/luacheck)
- [ ] support for VSC via LSP [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)

## Develop / Contribute
Any help via pull requests, test reporting, bug detecting, procedural aid and other
contributions are welcome on [github/SwissalpS/luaValidationToolkit](https://github.com/SwissalpS/luaValidationToolkit)

## License
If not stated otherwise in sub-modules or code files, this project is copyright protected under the [MIT license](LICENSE).
2025 SwissalpS
