# DEPRECATED Git Style Guide, see documentation wiki

## Branches

- There are 3 main branches. master, development, and staging. 
- **Never work in any main branch directly**
- Merging should be handled on Git Hub.
- Features should be prefixed with `feature/`
- Features should be branch off of development.
- Features must be merged into development.
- Bug fixes should be prefixed with `bug/`
- Only development should be merged into staging.
- Only staging should be merged into master. (this is not enforced right now. once we have a QA department it will be.)
- Once a branch has been merged into a main branch it should be deleted.


## Tags

- When merging branches into master you must include a release tag for example `git tag -a v2.22.2`
- Use the semantic version for the tag name. `-a v2.22.2` 
- Be sure to bump the version number with each tag.

References:

- [Git Tagging](https://git-scm.com/book/en/v2/Git-Basics-Tagging)
- [Semantic Versioning](http://semver.org/)

## Commits
- Each commit should be a single logical change. 
- Don't split a single logical change into seceral commits.
- Commit early and offiten
- Push each commit to Git Hub as they are made.


## Messages

- When adding a commit or tag message use your editor, not the terminal.






