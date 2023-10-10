# Listen.me

This is the read-me with instructions for cloning the project and where all the files and project segments are.

This project is separated into 4 repositories:
- WEB_MSRN_Listen.me
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me
    - This is the parent project with all the submodules pointing to all the project segments. It contains full project documentation and overall resources of the project as well as pointers to the other project segments
- WEB_MSRN_Listen.me-BeckEnd
    - URL: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me-BackEnd
    - This is the back-end part of the project and it contains all the necessary code and files for the back end. It is linked to the 03_BackEnd folder in the parent project.
- WEB_MSRN_Listen.me-FrontEnd
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me-FrontEnd
    - This is the front-end part of the project and it contains all the necessary code and files for the front end. It is linked to the 04_FrontEnd folder in the parent project.
- WEB_MSRN_Listen.me-ToolsAndPlugins
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me-ToolsAndPlugins
    - This is the part of the project that contains all of the additional tools and plugins created for the project and all necessary code and files for the tools and plugins. It is linked to the 05_ToolsAndPlugins folder in the parent project.

## Cloning the whole project

### Cloning with SSH (recommended)
First, you need to clone the parent project
``` 
git clone git@github.com:Tikky-Dev/WEB_MSRN_Listen.me.git
```
After you need to initialize submodules by going into a project and then initializing the submodules
```
cd ./WEB_MSRN_Listen.me/
git submodule init
```
The only thing left is to update submodules
```
git submodule update
```
### Cloning with HTTP (not recommended)
First, you need to clone the parent project
``` 
git clone https://github.com/Tikky-Dev/WEB_MSRN_Listen.me.git
```
After you need to initialize submodules by going into a project and then initializing the submodules
```
cd ./WEB_MSRN_Listen.me/
git submodule init
```
The only thing left is to update submodules
```
git submodule update
```

## Documentations
**Overall documentation:**
- located in the parent project in folder 01_Documentation
- File name is ReadMe.md
- you can find it [here](./01_Documentation/ReadMe.md)

**Back-end documentation:**
- partially located in overall documentation and extensive documentation in the read me file in the project repository (folder 03_BackEnd)
- File name ReadMe.md
- you can find extensive documentation [here](./03_BackEnd/ReadMe.md)

**Front-end documentation:**
- partially located in overall documentation and extensive documentation in the read me file in the project repository (folder 04_FrontEnd)
- File name ReadMe.md
- you can find extensive documentation [here](./04_FrontEnd/ReadMe.md)

