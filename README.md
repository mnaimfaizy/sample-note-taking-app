# sample-note-taking-app
Sample note taking app developed in Node.js and yargs library for creating a CLI application

## About project
This project can allow a user to `add`, `remove`, `list` and `read` the notes in a `json` format

To work with the application you can follow these commands:

This command will list all the notes
```
node app.js list
```

This command will create a note by passing the title and body
```
node app.js add --title "hello" --body "world" 
```

This command will read a single note from the json file
```
node app.js read --title a
```
This command will remove a single note from the json file
```
node app.js remove --title a
```

You can also see the details of a command by typing bellow command with each:
```
node app.js add --help
node app.js remove --help
node app.js list --help
node app.js read --help
```


## Quick Start
To use the application first you need to clone it and then run `npm install` to install the depndencies

