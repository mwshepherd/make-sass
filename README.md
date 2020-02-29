# MAKE-SASS Startup Script

A simple terminal bash command for initializing a SASS project

---

## Install

1. Download the script and copy to your /bin directory
2. Initialize the script with:

```bash
chmod u+x make-sass
```

3. Run the script in your desired working directory to create a working SASS project and start SASS --watch

```bash
make-sass
```

---

## Project Layout

This command will create the following files and working directories:

```
sass
│   main.scss
│
└───1-abstracts
│   │   _1-abstracts.scss
│   │   _variables.scss
│
└───2-base
│   │   _2-base.scss
│   │   _global.scss
│   │   _typography.scss
│   │   _utilities.scss
│
└───3-layout
│   │   _3-layout.scss
│
└───4-modules
│   │   _4-modules.scss


styles
│   style.css
```

Every module will be automatically linked together, SASS will run and create your complied CSS file in the /styles directory
