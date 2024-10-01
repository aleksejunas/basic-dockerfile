# Basic-dockerfile for the roadmap.sh site DevOps section

## How To

1. Add a folder with the name `HelloCaptain` # or whatever you want it to be called
2. `cd` into the folder
3. Create a dockerfile `Dockerfile`
4. Add to the Dockerfile: 
```
# Use the alpine base image
FROM alpine:3.12 # replace 3.12 with your desired version
CMD ["echo", "Hello, Captain!"]
 ```
5. Build and run the Dockerfile with:
`sudo docker build -t hello-captain .`
6. Watch as it pulls down the alpine Linux image and runs the command inside the container you made

## Project Page URL: [[https://roadmap.sh/projects/basic-dockerfile]]
