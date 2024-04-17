# homework-react - News Blog Web Application
Coding test for an interview showing React, Typescript + Docker container. 

## List of technologies, libraries and frameworks being used in this project
- JavaScript
- React
- Typescript
- Docker
- Tailwind

## How to run in development mode
Make sure you have Node.js v18+ installed on your machine

1. Clone the repository
2. Run `npm install`
3. Run `npm dev` to run it in development mode

## How to run in Docker
Make sure Docker is installed on your machine

1. Clone the repository
2. You have to build the image, running this command: `docker build -t homeworkreact-docker .`
3. To run the application, run this command`docker run -p 3000:3000 homeworkreact-docker`
4. Go to `localhost:3000` to use the application