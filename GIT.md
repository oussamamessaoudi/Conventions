# GIT
Every feature MUST (even if it's just a simple FIX) be in a NEW branch of type "Draft" status after development complete convert it to "Done" status for review.

## BRANCH

**Format**: *XXX-ZZZ_ZZZ_ZZZ_ZZZ-YYY*

- **XXX**: First letter of your first name followed by two letters of your last name
- **ZZZ**: Name of the branch (must be significant to the development made).
- **YYY**: TThe name of the branch that will be merged with master, develop ...


## COMMIT MESSAGE

Use a commit **TAG** in each message. This tag should be one of:
- **[IMP]**: For improvements.
- **[FIX]**: For bug fixes.
- **[REF]**: For refactoring (improvements of the source code, without changing the functionality or behavior. See http://en.wikipedia.org/wiki/Refactoring for further details).
- **[ADD]**: For adding new resources.
- **[REM]**: For removing of resources.

### Format: 
`TAG MODULE: COMMIT MESSAGE` <br/>
`SUITE OF COMMIT MESSAGE`

### Avoid big commits
Don't make a commit that will impact lots of modules. Try to split it into different commits where impacted modules are different (It will be helpful when we are going to revert that module separately).
