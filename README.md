# Notes

An Android app, written in Java. It is made for the Udemy course, The Complete Android N Developer Course by Rob Percival. The goal is to make a note app, where you can add and delete notes.

# What I learned

* Made two activities, using the Intent object that either is called with no extra arguments from the activity_main or it has args passed from it.
* Developed a UI within the two xml files using RelativeLayout, ListView and EditText.
* Implemented functionality to the UI using: onCreate, onCreateOptionsMenu and onOptionsItemSelected.
* Integrated setOnItemClickListener, when a note in the ListView is clicked, it gets to the NoteActivity with the information about the note. 
	setOnItemLongClickListener is called every time that user wants to delete a note.
* Used the addTextChangedListener, in the NoteActivity, so each change in the processing in the note is saved.