# Frontend Cinema Platform

<p>
This frontend simulates a cinema platform, it is designed to consume several microservices to perform its different actions. It accesses these microservices through defined URLs that point to the microservices defined in the backend. Each microservice has its internal logic to process the respective action. The availability of the functions will depend on the role that the user has at the moment of logging into the application.
</p>


#### How to install and run the project? :wrench:
The project requires Node.js and npm installed on your system. To install and run this frontend you must perform the following steps:

###### Clone the repository:

- `git clone <URL_OF_REPOSITORY>`
- `cd <URL_OF_REPOSITORY> `

###### Install dependencies:

- `npm install`

###### Execute the server:
- `npm start`


> [!NOTE]
> This fronted is done in REACT so the default port of execution is 3000.


#### How to use the project :computer:
<p>
To use this application you need to install and run the respective microservices you want to test, and modify the URLs according to your needs, once the frontend and microservices are running you can use them.
</p>

#### Microservices repositories:

- **Users**: <https://github.com/JaviQuilumba/MicroservicesUsers.git>
- **Movies**: <https://github.com/JaviQuilumba/MicroservicesMovies.git>
- **Snacks**: <https://github.com/JaviQuilumba/MicroservicesSnacks.git>
- **Theaters**: <https://github.com/JaviQuilumba/MicroservicesTheaters.git>
- **Info**: <https://github.com/JaviQuilumba/MicroservicesInfo.git>
- **Releases**: <https://github.com/JaviQuilumba/MicroservicesReleases.git>

#### Technologies used for these microservices
- **Node.js** with the Express.js framework for the backend server.

###  License 
This project is licensed under the (AFL-3.0) License - see the [LICENSE](https://opensource.org/license/afl-3-0-php) file for details.
