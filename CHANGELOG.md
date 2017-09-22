##### 2.0.3 - 22 September 2017

###### Bug fixes
- Fixed --help and --version flags

##### 2.0.2 - 22 September 2017

###### Backwards compatible changes
- Made command logs more consistent

##### 2.0.1 - 22 September 2017

###### Backwards compatible changes
- #36 - Automatically write a JavaScript appropriate .gitignore

###### Bug fixes
- Fixed release script

###### Other
- Updated contributing guide

##### 2.0.0 - 22 September 2017

Stable 2.0.0 release

###### Bug fixes
- #35 - Fix logger stutter

##### 2.0.0-beta.12 - 20 September 2017

###### Breaking changes
- Changed signature of `lint` command to match that of the `test` commands, i.e. using `--cmd` and `--` for args.

###### Other
- Improved repository URL handling
- Upgraded dependencies

##### 2.0.0-beta.11 - 19 September 2017

- Small tweak to the `lib_readme` template.

##### 2.0.0-beta.10 - 18 September 2017

- Fixed typo in `lib_readme` template.

##### 2.0.0-beta.9 - 18 September 2017

- Make `lib_readme` quickstart sample region tag configurable.
- Improve the look of the samples list in `lib_readme`.

##### 2.0.0-beta.8 - 18 September 2017

- Updates to `templates/nodejs/jsdoc.tpl`

##### 2.0.0-beta.7 - 07 September 2017

- Added 6 new targets to the `generate` command.
- Added `shell: true` to improve stability of CLI commands.

##### 2.0.0-beta.6 - 29 August 2017

- Added `templates/` to distribution (it was missing)

##### 2.0.0-beta.5 - 29 August 2017

- Fix Release Quality badge in lib_readme
- #23 - Add syntax highlighting to quickstart sample in lib_readme
- Fix relative Github links in lib_readme
- #22 - Add support for year ranges in the license file.

##### 2.0.0-beta.4 - 23 August 2017

- Fix: `utils.fatal` => `utils.logger.fatal`

##### 2.0.0-beta.3 - 21 August 2017

- Added `yargs-parser` to list of dependencies.

##### 2.0.0-beta.2 - 21 August 2017

- Add use of babel-preset-env to prepublish step to product a Node.js v4
  version of Repo Tools.
- Added `tools exec -- <cmd> [args..]` command.
- Now testing on more Node.js version (though the testing on Node.js v4 is just
  a smoke test).

##### 2.0.0-beta.1 - 21 August 2017

- Add support for generating client lib files.
- Upgraded dependencies.
- Refactored build pack objects to classes
- Improved README and added contributing guide