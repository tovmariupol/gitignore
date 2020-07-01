# Labs "Learning GIT. Using file .gitignore"

This task helps students to understand the purpose of the .gitignore file.

## Tasks

1. Clone repository https://github.com/dbielik/mdt
2. Include only:
  - www/css folder - only .css files;
  - www/js folder - only .js files;
  - www/min folder - only files with '-min' in name;
3. Allow png/jpg/jpeg files only in www/img folder
4. Exclude .code folder for all repositories

### Implementation

To study and verify the execution of work, you can clone this repository to your machine. Check the contents of the files both in the main folder and in the subfolders of the project.

To exclude the .code folder from all projects for the local user, you need to run the command:

 git config --global core.excludesFile .code  

## Checking

Verify by adding different files in respective folders 

## Versioning

v0.0.2


## Authors

Oleh Tyshchenko

