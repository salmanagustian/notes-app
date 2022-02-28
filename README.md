# Notes App ✏️
Keep your notes. 

## Project Setup
```
  npm install
```

## List of commands
| Command | Description |
| --- | ----------- |
| app.js add | Add a new note |
| app.js remove | Remove a note |
| app.js list | List your notes |
| app.js read | Read a note |

## List of attributes

| Attributes | Description | Required
| --- | -------- | ---
|--title | A title of note | Yes
|--body | A body of note | Yes

### Example command

1. Add a note
```
node app.js add --title='My Awesome Note' --body="Some body"
```
2. List notes
```
node app.js list
```
3. Remove a note
```
node app.js remove --title='My Awesome Note'
```
4. Show a note
```
node app.js read --title='My Awesome Note'
```
