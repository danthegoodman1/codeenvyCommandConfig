# codeenvyCommandConfig
Quick config for running Run commands on Codeenvy

### "Command Line"
You start in the /projects folder, which is the parent folder for all projects.

If I wanted to run `hello.js` in the `testProj` project, I would have the command:

`node testProj/hello.js`

### Preview URL
*Make sure that the project you want to run is enabled if you want it to be internet exposed*

`http://${server.port.8080}`

I used that to expose an express server running on port 8080 to the internet. You can get the actual URL that your project will be running on by running the command, then clicking the button in the very top right and clicking the one that says:

`dev-machine:$PORT` where `$PORT` is the port you are running your service on. That will take your browser to the link that the app is running on and will continue to be that link until you stop the workspace.

### Other notes about Codeevny:
- On macOS, using option works for deleting and moving by word, but using command only works for moving by line, not deleting line
- Can use Command-S to save on macOS
