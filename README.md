# NotesWise
- A CLI tool build using javascript and various node js cli tool building package

# APP Setup
- Run "npm install" 
- Run app.js with the help of the following command "node app.js"

### Adding Note
- To add a note use "add" command
- Use --title to add title
- Use --body to add the task
- Both flags are necessary
- Cannot add notes with same title
- Example usage => node app.js add --title="Note title" --body="task 1, task 2,.."

### Remove a note
- To remove the note use 'remove command also pass the '--title=<your title>' for removing the note
- Examole usage => node app.js remove --title="Note title"


### Listing all notes
- To list all the notes use 'list' command
- Example usage => node app.js list


### Reading a note
- To read the particular note use 'read' command along with '--title=' flag
- Example usage => node app.js read --title="Note title"


### Appending to a note
- To add the task to the existing notes '--title=' and '--body=' to add the task into the existing one
- Example usage => node app.js append --title="Note title" --body="task 3, task 4,.."



