# package-the-module-lp-author
Repository for liveProject: Package the Module
This repository contains starter files for the third project in the series - these very files are actually a full solution for the second project about testing the PowerShell module.
## How to get started
After completing the setup and installing the required dependencies for this project, and forking and cloning this repository, you should be able to run build.ps1 file which would create a fully functioning module in the build directory.
At this point the project is good to go, please follow the steps from the workflow.
There's also a GitHub workflow to build the module automatically upon pushing it to the Main branch - you might need to enable the workflow.
## Significant files and folders
* build.ps1 file - the main building file. This file takes all source files from the /source/ directory and compiles the module into /build/ directory
* /source/ directory - contains all .ps1 files, and module manifest in the .psd1 file. File in the /source/public/ directory are usable by the user after building and importing the module
* /.github/workflows/ci.yml file - the GitHub action which builds the module
