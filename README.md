# Best Restaurants
This website lets users add their favorite restaurants based on the type of cuisine they offer.

#### By Karen Axon

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Technologies Used
* C#
* AspNetCore
* .Net5
* HTML
* CSS
* Bootstrap
* Entity Framework Core
* MySql
* LINQ

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Setup/Installation 
* Click on the [repository's](https://github.com/karenaxon/BestRestaurants.git) link.
* Click on the green "Code" button and copy the repository URL.
* Open your terminal and navigate to the location where you would like to clone the application.
* Use the command _git clone https://github.com/karenaxon/BestRestaurants.git_ to clone the repository.
* From the top level directory, navigate to the BestRestaurants folder and run the following commands:
  - _dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0_ 
  - _dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2_
  - _dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0_			
* Open the application in your favorite text editor to make changes.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Setting up the database 

![Alt text](BestRestaurants/wwwroot/images/db_schema.jpg?raw=true "Title")

After following the Setup/Installation steps above open the database dump file in MySQL Workbench:
* Start a local instance 3306.
* In the Navigator > Administration tab select _Data Import/Restore_.
* In _Import Options_ select _Import from Self-Contained File_.
* Navigate to the BestRestaurants.Solution folder and locate the file database dump file.
* Click _Ok_.
* Navigate to the tab called _Import Progress_ and click _Start Import_ at the bottom right corner of the window.
* In the Navigator > Schemas tab, right click and select _Refresh All_.
* Navigate to the BestRestaurants folder of the project and create an _appsettings.json_ file with the following code (making sure to delete the [] and replace the name of the database and the corresponding):
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[data_base_name];uid=root;pwd=[password];"
  }
}
```


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Using the Application
After following the Setup/Installation and setting up the database (steps above): 
  * Navigate to the BestRestaurants folder.
  * Start the application in a server with the command _dotnet run_.	

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## Known Bugs
* None

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) December, 2021 - Karen Axon

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)


## Contact Information:

<h3>Karen Axon</h3>

[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karenaxon)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaxon)
