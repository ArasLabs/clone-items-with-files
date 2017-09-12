# Methods to Clone Items with Files
The methods in this import add functionality to for the CAD and Document Items that will allow users to create duplicate File items when they clone an Item with a relationship to File.

## History
This project and the following release notes have been migrated from the old Aras Projects page.

|Release|Notes|
|-------|---------------------------------------------|
|v1     |Cloning CAD and Document Item                |
|v2     |Cloning CAD and Document Item updated for 9.4|

### Support Aras Versions
|Project|Aras |
|-------|-----|
|v1     |9.3.0|
|v2     |9.4.0|

## Installation
**Important!
Always back up your code tree and database before applying an import package or code tree path!**

### Pre-requisites
1. Aras Innovator installed
2. Aras Package Import tool
3. **Clone Items with Files** import package

### Install Steps
1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool
3. Enter your login credentials and click **Login**
⋅⋅* _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
⋅⋅* Optional: Enter a description in the Description field
5. Enter the path to your local `..\CloneFilesWithItems\Import\imports.mf` file in the Manifest File field
6. Select all in the Available for Import field
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

# Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

# Credits
Created by Aras Corporation Support

# License
Published to Github under the MIT license. See the [LICENSE File](../blob/master/LICENSE.md) for license rights and limitations.
