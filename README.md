## Check the README file in the node server project (regarding environment file config)

### Clone the project into your local machine

### Run the below commands to initialize the local configuration file and to fetch all the data from the linked projects

#### git submodule init

#### git submodule update

### Run the below command to build, create/recrate the images and attach them to containers and create a network and volume as defined in the docker-compose.yml file

#### docker-compose up --build

### Run the below command to stop and remove the containers, images, network and volume created by the up command

#### docker-compose down
