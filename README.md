### ts-test-node_modules

After cloning this repo, test the code by running the following commands:

`npm install`

then

`npm run build`

then

`npm run postbuild`

A `./dist` folder should be created, containing the following folder/files:
- node_modules (note that only the modules used in index.ts will end up here)
- index.js
- package.json
- package-lock.json


##### References:
###### https://stackoverflow.com/questions/41109461/how-include-node-modules-in-output-directory-with-typescript/42162316#42162316
###### https://www.youtube.com/watch?v=mxiRCcnsKDw