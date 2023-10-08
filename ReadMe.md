# Listen.me

This is the read me with instructions for cloning the project and where all the files and project segments are.

This project is seperated in 4 repositories:
- WEB_MSRN_Listen.me
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me
    - This is the parrent project with all the submodules pointing to all the ptoject segments. It contains full project documentation and overall resources of the project as well as pointers to the other project segments
- WEB_MSRN_Listen.me-BeckEnd
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me-BackEnd
    - This is the back end part of the project and it contains all the necessary code and files for the back end. It is linked to the 03_BackEnd folder in the parent project.
- WEB_MSRN_Listen.me-FrontEnd
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me-FrontEnd
    - This is the front end part of the project and it contains all the necessary code and files for the front end. It is linked to the 04_FrontEnd folder in the parent project.
- WEB_MSRN_Listen.me-ToolsAndPlugins
    - url: https://github.com/Tikky-Dev/WEB_MSRN_Listen.me-ToolsAndPlugins
    - This is the part of the project that contains all of the additional tools and plugins created for the project and all necessary code and files for the tools and plugins. It is linked to the 05_ToolsAndPlugins folder in the parent project.

## Cloning the whole project

First you need to clone the parent project (⚠️ This is the implementation with ssh)
``` 
git clone git@github.com:Tikky-Dev/WEB_MSRN_Listen.me.git
```
After you need to initialise submodules
```
git submodule init
```
Only thing left is to update submodules
```
git submodules update
```