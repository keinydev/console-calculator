# Running proyect

## Install dependencies
npm install

## Compile code
npx tsc

## Running app
node dist/index.js

## Execute tests
npm run test

# Using docker

## Generate image
docker build -t calculator-app .

## Running app
docker run -it --rm calculator-app
