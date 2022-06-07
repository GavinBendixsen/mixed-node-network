# mixed-node-network
Docker scripts for testing a network with a mix of versions for consensus

# Commands
To build the images
- docker build -f "build/Dockerfile.ubuntu16" -t indy_node:latest-ubuntu16 ./build
- docker build -f "build/Dockerfile.ubuntu20" -t indy_node:latest-ubuntu20 ./build
To start the mixed network
- docker-compose -f docker-compose.network-mixed.yml up
