## Go Parse
###### :tada: Version: `v1.0.0-alpha`

### Usage
```bash
./go-parse -h


Usage of ./go-parse:
  -d string
    	the project path to generate release note (default ".")
```

### Pre-requisite
We are only supporting the semantic message format mathing the following template


```
feat (ticket): create a death start
^--^ ^-------^ ^------------------^
|        |          |
|        |          +-> Summary in present tense.
|        |
|        |
|        +--> Jira tecket id for the task (ie, EHH-93), this is optional
|
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat` (EFR-XXX): (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `doc` (SDT-XXX): (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`(SLD-XXX): (refactoring production code, eg. renaming a variable)
- `test` (BDT-XXX): (adding missing tests, refactoring tests; no production code change)
- `chore` (FET-XXX): (updating grunt tasks etc; no production code change)

---
### :wrench: Fixes
* :ballot_box_with_check:  dependency added
* :ballot_box_with_check:  improvement tag and some edge cases handled
* :ballot_box_with_check:  readme generation format, build automation
### :mega: Features
* :high_brightness:  dependency added
* :high_brightness:  improvement tag and some edge cases handled
* :high_brightness:  readme generation format, build automation
### :white_check_mark: Tasks
### :clap: Improvements
### :clipboard: Documents
*  generated documentation
*  gitignore for golang
*  project level documentation
### :syringe: Tests
*  generated from this cli
### :triangular_flag_on_post: Extras
- :no_entry:  new tag for commits added


### Contribute
This is a work in progress, please raise issues, add improvements, and edge cases. I intend to work on each ticket.
for more details please feel free to drop a mail
<a href="mailto:me@sabbir.dev?"><img src="https://img.shields.io/badge/gmail-%23DD0031.svg?&style=for-the-badge&logo=gmail&logoColor=white"/></a>

or drop a text at [telegram](https://t.me/tosabbir)