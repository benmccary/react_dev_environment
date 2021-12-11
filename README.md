## How I make this thing work (and useful commands)

This creates a new app in the format that I need for my docker build
`npx create-react-app my-app`

This composes the docker image
`docker-compose -f docker-compose.dev.yml up`

This runs the already existing docker image
`sudo docker start app-dev`


Other than that, I used the code on [this youtube video](https://www.youtube.com/watch?v=1QK27MUr2Dk&t=312s) from [this tutorial](https://dev.to/karanpratapsingh/dockerize-your-react-app-4j2e).