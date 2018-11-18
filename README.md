# Simple Notes App With Node.js

This is a simple note application that can be used to add, read, and delete notes into a json file. The app is created using Node.js so you will be reading a javascript (ES6) code.

### Setup

To run the note app in your local computer, install the dependencies listed in the package.json file. To install all of the dependencies, run the following command
```
npm install
```
Make sure you have npm installed in your computer

### How to used

The application has 4 command: add, list, read, remove.
<br/>
The add command will add a single note into notes-data.json file. This command need to receive two flags:
- title
- body

```
node app.js add -t "Note 1" -b "Body of note 1"
```

<br/>
The list command will print all notes inside notes-data.json file

```
node app.js list
```

<br/>
The read command will read a single note from notes-data.json file.
This command need to receive one flag:
- title

```
node app.js read -t "Note 1"
```

<br/>

The remove command will delete a note from notes-data.json file.
This command need to receive one flag:
- title

```
node app.js remove -t "Note 1"
```
