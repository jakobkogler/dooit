# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0 [Unreleased]

### Added 

- **A whole new API to interact with dooit** (closes https://github.com/kraanzu/dooit/issues/23)
- **Unlimited brancing of todos and workspaces** (closes https://github.com/kraanzu/dooit/issues/85 and https://github.com/kraanzu/dooit/issues/70 and https://github.com/kraanzu/dooit/issues/58)
- **Smart node addition on <enter>**
  - Dooit now will not add an extra item automatically if you are just editing description of some node
- **Support for edit and addition in SEARCH mode**
  - Previously users were only allowed to jump to the todo
- **Synchronisation between multiple instances** 
  - Previously dooit printed a warning and exited with a message indicating that it's already running (closes https://github.com/kraanzu/dooit/issues/49)
- **New parameters for todos!**
  - **Recurrence** ==> Adds recurrence to todos for regular reminder!
  - **Effort** ==> An Integer Value to determine the effort/time it will take to complete the todo (for https://github.com/kraanzu/dooit/issues/74)
  - **Tags** ==> Add tags to todos
  - **Time** ==> Previously ony date was supported (closes https://github.com/kraanzu/dooit/issues/66)
- **Better date&time parsing** 
  - Dooit now uses [dateparser](https://pypi.org/project/dateparser/) module to make it a lot easier to add and edit date&time (for https://github.com/kraanzu/dooit/issues/71)
- **Custiomizable Bar**
  - Dooit now has a bar that can be customized to your liking!
  - You can now use python scripts to display your desired content in the bar
  - You can also use dooit API to display info in status bars
- A better config parser which handles ovveriden case better! (closes https://github.com/kraanzu/dooit/issues/64)

### Fixed
  - Update textual which might fix several issues! (maybe closes https://github.com/kraanzu/dooit/issues/57 and https://github.com/kraanzu/dooit/issues/57)
  - Using '/' in todos crashes app (closes https://github.com/kraanzu/dooit/issues/84)
  

### Changed
  - Remove mouse support...coz why not? (closes https://github.com/kraanzu/dooit/issues/69)
  - Some keybindings
  - Unicode by default (remove nerd font icons from default config)
  - match-case stmts (Adds support for python>=3.7)
  
