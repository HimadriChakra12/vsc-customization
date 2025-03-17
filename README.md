# Customization
## Themes
I choose Gruvbox as my goto theme so it installed,

    1. Gruvbox material for Color-Sceme
    2. Gruvbox matrial icons for File Icons
    3. Carbon for product icons
## Extensions
I use some extensions for my productivity in VSCode so I installed,

    1. Vim
    2. Powershell
    3. GitLens
    4. Github Copilot
    5. Code Runner
    6. advanced-new-file
## nvchad Experience
I used to code in nvchad(as it was readymade) in neovim. But the installation didn't work well this time. So I have to switch to my familiar IDE, Vscode. But I miss some of the features of nvchad. The Telescope plugin and cd command are the  plugins I missed the most. So I made some of mine that mimics them,

    1. cdvsc
    2. Zoxide-like
    3. fuzzy-finder
## For C Language
As the mother of all languages, it is used to teach the basics of programming. So, it is academically taught to us. As a result I used to make my vscode as compatable as possible for writing and running C programs. So, I needed a compiler for that. The most familiar of all compiler is mingw cause it has all needed ones.

To Run that, you can run the following command on powershell

irm "https://github.com/HimadriChakra12/vsc-customization/raw/main/mingw.ps1" | iex

then it will automatically download the file and  open the installer. Install it and click on the close button, it will open the installation manager window, select/mark needed features then in the installation menu click apply changes, it will install the selected features.

Then it will add the path of mingw to the system.
