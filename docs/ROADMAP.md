# Roadmap

## Introduction

This page list the status of all included and future features to be added to project

## MVP Todo's

- [ ] Create User Login Page
- [ ] Re-direct user to chibihub.com if not already registered

#### project ticket example:
```markdown
1. (package/file/tool/program) | (action)
   - [ ] status: (option) 
      - (backlog) | feature to be implemented
      - (staged) | feature installed/linked/setup in project
      - (in-progress) | actively working on feature
      - (complete) | all feature detailes completed

   - [ ] features:
      - [ ] (file/package/program) | (details)
   
   comments:
      - Lorem ipsum dolor sit amet, consectetur adipiscing elit.
      - Aenean at lorem a odio facilisis sollicitudin sit amet at nisl.
      - In hac habitasse platea dictumst. Nunc rutrum vitae ante non maximus.
```

## Setup Project

**1. github | create git repository**

   - [x] **status:** *complete*

**2. github | utilize biolerplate**

   - [x] **status:** *complete*

**3. github | license**
   
   - [x] **status:** *complete*

**4. github | sematic versioning**
   
   - [ ] **status:** *backlog*

**5. package manager | yarn 2**

   - [ ] **status:** *in-progress*
   - [ ] **features:**
     - [x] .gitignore | add files to be ignored
     - [ ] .gitattributes *(if needed)*


**6. formatting | .editorconfig configure**

   - [ ] **status:** *backlog*

**7. formatting | add prettier**

   - [ ] **status:** *backlog*

**8. documentation | add docsify to project**

   - [x] **status:** *complete*

**8. docsify | deploy**

   - [x] **status:** *complete*
   - **comments:**
     - deployed through github pages

**9. docsify | themes**

   - [ ] **status:** *backlog*
   - [ ] **features:**
     - [ ] choose theme

**10. docsify | helpers**

   - [ ] **status:** *backlog*
   - **comments**
     - docsify helpers available to further customize docsify

**11. docsify | plugins**

   - [ ] **status:** *backlog*
   - [ ] **features:**
     - [ ] *[Full text search](https://docsify.js.org/#/plugins?id=full-text-search)*
     - [ ] *[emoji](https://docsify.js.org/#/plugins?id=emoji)*
   - **comments**
     - docsify plugins available to further customize docsify

**12. readme | badges**

   - [ ] **status:** *backlog*

**13. ...**

## User Interface

**1. extention | icons**

   - [x] **status:** *complete*
   - **comments:**
     -  uploaded icons to img folder & added icons to manifest.json
  
**1. popup | create**

   - [ ] **status:** *backlog*   

**2. popup | setup auth0 register/login**

   - [ ] **status:** *backlog*

**3. popup | css**

   - [ ] **status:** *backlog*

**4. popup | icons**

   - [ ] **status:** *backlog*

**5. popup | font**

   - [ ] **status:** *staged*

   - **comments:** 
     - fontawesome link added to popup html

**6. ...**

## Database

**1. Setup PouchDB Local**

   - [ ] **status:** *backlog*

**2. Sync PouchDB to Remote**

   - [ ] **status:** *backlog*

**3. ...**

## Features | Base

**1. feature | Like/Dislikes**

   - [ ] **status:** *backlog*

**2. feature | User Stats**

   - [ ] **status:** *backlog*

**3. feature | Settings**

   - [ ] **status:** *backlog*

**4. ...**

## Features | Optional

**1. background.js | automatically add bookmarks to like**

   - [ ] **status:** *backlog*

**2. ...**

---

## Resources

### Github | Boilerplate

- [samuelsimoes](https://github.com/samuelsimoes/chrome-extension-webpack-boilerplate)

### Fontawesome | Fonts

- [fontawesome/kits](https://fontawesome.com/kits)
- [fontawesome/sizing](https://fontawesome.com/docs/web/style/size)
- [fontawesome/animating-icons](https://fontawesome.com/docs/web/style/animate)
- [fontawesome/styling](https://fontawesome.com/docs/web/style/styling)
- [fontawesome/icons](https://fontawesome.com/icons)

### Auth0 | Chrome Authentication

- https://community.auth0.com/t/ultimate-guide-to-auth0-in-a-chrome-extension-popup/61362/2
- https://community.auth0.com/t/auth0-in-chrome-extension-content-background-script-mv3/74603
- https://roberttolton.com/posts/implementing-auth0-authentication-into-a-chrome-extension
- https://auth0.com/docs/get-started/authentication-and-authorization-flow/call-your-api-using-the-authorization-code-flow-with-pkce

### PouchDB | Ext Storage

- [Replication](https://pouchdb.com/guides/replication.html)

### PostgreSQL | Original Database Storage  

- [PostgreSQL Link](https://www.elephantsql.com/)
