# Minecraft Extended
Welcome to the project files for the Minecraft Extended modpack.
***
## How to work on the modpack
1. Download [packwiz](https://github.com/packwiz/packwiz).

2. Set your environment variables to reference its location.

>**Example**: Set your .zshrc file to include this `export PATH=$PATH:/opt/packwiz`

3. Clone the project.
```
git clone git@github.com:w1zz4rddr4g0n/Minecraft-Extended.git
```
4. Make sure you're in the project directory.
```
cd Minecraft-Extended
```
5. Use packwiz to execute desired changes.

>Add a mod use this command `packwiz mr install modname`

>Update the mods use this command `pcakwiz update --all`

>Remove a mod use this command `packwiz remove modname`

>Export the modpack into a usable format by polymc use this command `packwiz mr export`

>Change the modpack version number and forge version used edit the `pack.toml` file