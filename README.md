# GIPMO Online

## Installation

- Run the database: Install [MySQL](https://dev.mysql.com/downloads/installer/) and configure the server with
        `user: root`
        `password:root`. Create a new schema named `gipmo-online`.

- Install and run the front-end:


    yarn install && yarn start


- Run the back-end:


    ./mvnw

## Building for production

To generate a production build, please run:

    ./mvnw -Pprod clean package
