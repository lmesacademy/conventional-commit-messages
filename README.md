# Conventional Commit Messages


```
<type>(<optional scope>): <subject>
```


### Types

1. `feat` - new feature
2. `fix` - bug fix
3. `pref` - performance improvements
4. `refact` - refactoring ( rewrite/restructure code with no change in behaviour )
5. `style` - formatting ( no code changes )
6. `test` - adding missing tests or correcting existing tests
7. `docs` - documentation changes
8. `chore` -  miscellaneous commits (eg. version release, configuring .gitignore )
9. `ops` - infrastructure and deployment changes
10. `revert` - revert commit


### Scope

1. Scope is an optional part but, its highly recommended. It helps to indentify which part of the project the change is coming from.
2. Do not use ticket / issue id on scope

#### Sample scopes

1. Mono Repo with Frontend and Backend
    - runner
    - config
    - common
    - core
    - api
2. API Repo
    - middleware
    - config
3. Flutter App
4. Website
    - language
    - auth
    - service worker


### Subjects

1. Use present tense
2. Should not end with a [dot]
3. don't capitalize the first letter

| Right          | Wrong            |
|------------------|------------------|
| rename the vars  | renamed the vars |
| merge            | merged           |
| rebase           | rebased          |
| change           | changed          |



 

### Referencing issues

Closes #1, #2 , #721


### Sample commit messages

1. chore(release): version update 0.77.0
2. fix(deps): update flutter to 3.0.0
3. feat(login): add password reset
4. docs: add readme
