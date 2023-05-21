# _Hair Salon_

#### By _**Sierra Rhodes**_

#### _This application is a simple website that creates stylists and clients. It can assign a client a stylist_

## Technologies Used

* _C#_
* _ASP.Net_
* _MySQL_
* _Entity Framework Core_
* _HTML_
* _CSS_

## Description

_This is an application that creates a mock hair salon website that lets the user add, delete, and edit a stylist as well as clients. The clients are stored under a specifc stylist_

## Setup/Installation Requirements

* _Install MySQL Community Server and MySQL Workbench. _
* _Clone the repository to your desktop_
* _Change to the HairSalon directory and restore with $ dotnet restore_
* _run the application with $ dotnet watch run
* _create an appsettings.json file and add it to .gitignore file if not done already. 
* _within the appsettings.json file add:


{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[];uid= [];pwd= [];"
  }
  fill in the database, username, and password with your own information 
} _

## Known Bugs

* None

## License
Copyright 2023 Sierra Rhodes 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
