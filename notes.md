In general, after got a project files, first run npm install to actually download all the depencies described in packages.json and node-modules/ is generated as results. Then run npm build
or npm run webpack etc to build the actual js and dist/ is generated, for the build to work there is usually a config file and an entry point index.js in src/.
