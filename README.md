# Project Name

#### Independent Code Review
#### Created 01.21.2021 | Last Updated 01.21.2021

#### **By Chelsea Becker**

## 📊Project Overview

### Description

_An application to market Pierre's sweet and savory treats._

### Technologies Used

_VS Code_ <br>
_C# 7.3.0_<br>
_.NET Core 2.2.0_<br>
_Entity Framework Core 2.2.6_<br>
_MySQL Workbench 8.0 for Windows_<br>
_Postman_<br>
_Swagger_<br>
_Swashbuckle_


### Known Bugs

No known bugs at this time.

## 🔌Installation Requirements

### Code Editor

To open the project on your local machine, you will need to download and install a code editor. The most popular choices are Atom and Visual Studio Code https://code.visualstudio.com/. Visual Studio Code is the code editor used to create this application.

### Installing .NET Core Framework for Windows(10+) Users

1. _Download the 64-bit .NET Core SDK (Software Development Kit) by following this link: https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.203-windows-x64-installer._<br>
1a. _Follow prompts to begin your download. The download will be a .exe file. Click to install when it is finished downloading._
2. _After clicking the downloaded .exe file, follow the prompts in the installer and use suggested default settings._
3. _You can confirm a successful installation by opening a command line terminal and running the command_ `$ dotnet --version` _, which should return a version number._


### Installing .NET Core Framework for Mac Users

1. _Download the .NET Core SDK by following this link: https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer._<br>
1a. _Follow prompts to begin your download. The download will be a .pkg file. Click to install when it is finished downloading._
2. _After clicking the downloaded .pkg file, follow the prompts in the installer and use suggested default settings._
3. _You can confirm a successful installation by opening a command line terminal and running the command_ `$ dotnet --version` _, which should return a version number._

### Install Dotnet Script

1. _Enter the command `dotnet tool install -g dotnet-script` in the command line of a terminal window, such as Terminal for macOS or PowerShell for Windows._

### Installing MySQL Workbench

1. _[Download and install](https://dev.mysql.com/downloads/workbench/) the version of MySQL Workbench suitable for your machine._

### Install Postman (optional)

1. _Follow [this](https://www.postman.com/downloads/) link to view the Postman website to download and install._

## 💻View Locally/Project Setup

#### Clone
1. _Follow above steps to install .NET Core._
2. _Open web browser and go to https://github.com/cschweig2/Pierre.Solution._
3. _After clicking the green "code" button, you can copy the URL for the repository._
4. _Open a terminal window, such as Command Prompt or Git Bash._<br>
  4a. _Type in this command:_ `git clone` _, followed by the URL you just copied. The full command should look like this:_ `git clone https://github.com/cschweig2/Pierre.Solution` .
5. _View the code on your favorite text editor, such as Visual Studio Code._

#### Download
1. _Click [here](https://github.com/cschweig2/Pierre.Solution) to view project repository._
2. _Click "Clone or download" to find the "Download ZIP" option._
3. _Click "Download ZIP" and extract files._
4. _Open the project in a text editor by clicking on any file in the project folder._

#### Import Database in MySQL Workbench
1. _Open MySQL Workbench and enter your password to open a server._
2. _From the top navigation bar, follow:_ `Server > Data Import`.
4. _Select the option_ `Import from Self-Contained File`.
5. _Click the `...` button to navigate to the project file folder_ `Pierre` _and select_ `Pierre.sql`.
5. _Set_ `Default Target Schema` _or create new schema_.
6. _Select the schema objects you would like to import._
7. _To finalize, click_ `Start Import`.

#### Import Database with Entity Framework Core/Command Line
1. Navigate to the `Pierre` project folder and enter `dotnet ef database update` in the command line, which will create the database in MySQL Workbench using the migrations from the `Migrations` folder.

#### Final Steps
1. Navigate to the `Pierre` folder and enter `dotnet restore` in the command line to install packages.

2.After packages are installed in each of these folders, navigate to the `Pierre` project folder and enter `dotnet run`  in the command line to both run and build the program.

## 📄API Documentation

Explore our API endpoints with Swagger Documentation:
After entering `dotnet run` in the command line to launch the server, use a browser to navigate to `http://localhost:5000/swagger/`.

### Using Swagger Documentation
To explore the CoffeeTracker API with NSwag, launch the project using `dotnet run` with the Terminal or Powershell, and input the following URL into your browser: `http://localhost:5000/swagger`

#### Example Query
```
https://localhost:5000/api/
```
### Sample JSON Response
```
*enter response*
```
## 📧Support and contact details

_If you run into any issues, you can contact the creator at chelraebecker@gmail.com, or make contributions to the code on GitHub via forking and creating a new branch._

## 📝Contributors

<table>
  <tr>
    <th>Author</th>
    <th>GitHub Profile</th>
    <th>Contact Email</th>
  </tr>
  <tr>
    <td>Chelsea Becker</td>
    <td>https://github.com/cschweig2</td>
    <td>chelraebecker@gmail.com</td>
  </tr>
</table>

## 🧐Legal

*This software is licensed under the MIT license.*

Copyright (c) 2020 **Chelsea Becker**