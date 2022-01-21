# How to use

## Default project files

### Files inlude

- src folder
  - img folder
    - sample included can delete
  - js folder
  - scss folder
  - index.html
- .env_sample
  - rename to .env as needed
- .eslintrc
  - includes Wes Bos eslint package
- .gitingnore
- package.json

### Steps to get project started

1. Download zip file or clone repository
1. Rename zip folder or clone folder to project name.
1. Move project folder to "current project" location on comoputer.
1. Open project in editor or terminal
1. Enter command from command line in current project root directory folder
   - `npm install `
     - will install all dependencies listed in the package.json file
1. edit package.json file to rename project name to current project.

### Edit files in src folder

- index.html for all main html content
  - add additional html files here as well
- use scss files to create all css for project
- place all image assest in the img folder

### Start Development live server

- `npm run dev`
  - This will open project in your default browser. It will auto reload after saving any changes.
