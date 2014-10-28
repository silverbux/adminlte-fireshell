adminlte-fireshell
==================
AdminLte Fireshell - a free Bootstrap 3.x  admin dashboard template that is based on AdminLte combined with Fireshell Boilerplate

#Preview
!["AdminLTE-Fireshell"](https://raw.githubusercontent.com/silverbux/adminlte-fireshell/master/screenshot.png "AdminLTE-Fireshell")


# Installation
* Clone the repo: `git clone https://github.com/silverbux/adminlte-fireshell.git`
* Go inside the folder and Install Requirements: `npm install`
* Install Bower Components: `bower install`
* Run Grunt: `grunt`
* Open in browser: `localhost:9000`

#Customize / Modify / Workflow
`grunt` will monitor any changes to sass, css and js files and automatically combine, minify and clean all files to **app/assets/css/style.min.css** and **app/assets/js/script.min.js**

#Folder Structure

```bash
adminlte-fireshell
├──app
│  ├── assets           # json file containing all css files to combine
│  │    ├── components  # third party scripts
│  │    ├── css         # css files
│  │    ├── js          # js files
│  │    ├── img         # images files
│  │    └── fonts       # images files
│  │
│  ├── index.html       # json file containing all js files to combine
│  └── pages            # source files for css
│
├──src
│  ├── components       # third party script sources
│  ├── js               # js source files
│  ├── less             # less source files
│  ├── scss             # sass source files
│  └── tmp              # temporary folder
│
├── grunt-build.command
├── grunt-build.bat
├── grunt-dev.command
├── grunt-dev.bat
├── package.json
├── README.md
├── .editorconfig
├── .gitignore
├── .jshintrc
└── .travis.yml
```

# MORE INFO

## Installing Ruby and Sass
* https://www.ruby-lang.org/en/installation/ *(for windows user dont forget to check "Add Ruby executables to your PATH" option)*
* After installing Ruby execute `gem install sass` to install SASS

## CREDITS
AdminLte-Fireshell is simply a copy of AdminLte with fireshell under the hood. All necessary credits are given to [AdminLte](https://github.com/almasaeed2010/AdminLTE) authors.

## LICENSE
Bootflat-Admin is licensed under the MIT Open Source license. For more information, please see the LICENSE file in this repository.