# workbench
Runs the entire application with all the microservices

## Build and Run

1. Pull down the latest master branch for each service : **TODO: ADD BASH COMMAND TO AUTOMATICALLY DO THIS**
1. Download Docker for your machine
2. Run the following command: `docker-compose up --build`

**Note:** Takes a while the first time running that command because you are downloading some big dependencies. These dependencies are cached so running it a second time should be a lot faster

## Test
1. Go to http://localhost:8761/ (might take a little while before this port is open for business)
2. If the following instances are registered with eureka then you have a successful build
    * FORUM-SERVICE
    * POINT-SERVICE
    * SEARCH-SERVICE
    * USER-SERVICE
