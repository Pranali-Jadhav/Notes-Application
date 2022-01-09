# Notes-Application
Its an educational app for making essential notes.

<b>Problem Statement:</b>

To write down an important idea that is just struck, or a phone number we
often search for a paper nearby to quickly jot it down. But many times we
don’t find a paper and we miss on the important task we are doing. Mobile is a
very common device nowadays. A paper can be replaced with a mobile
application as it is very easy to access.

<b>Proposed Solution:</b>

The proposed solution includes a workspace where one can save essential
notes. An individual can edit, update as well delete the note. Individuals can
add multiple notes in the workspace and delete them simultaneously. One gets
an acknowledgment on adding, deleting, and updating the notes. It&#39;s a user-
friendly application.

<b>Screenshots of the app are: </b>

![1](https://user-images.githubusercontent.com/91827825/148681671-d8c0a7ca-0867-4c1a-8a80-b2e553f25556.png)


![2](https://user-images.githubusercontent.com/91827825/148681677-fba20623-024e-4fb9-85a3-1c72803d0d3f.png)

<b>Functionality and Concepts used:</b>

It is a very simple and user-friendly app where people can add, delete and update a note. The time and date on which the app was last updated are also seen with the notes. Following are android concepts used to achieve the functionalities in the app: 

 Constraint Layout: 

Most of the activities in the app use a flexible constraint layout, which is easy to handle for different screen sizes.

 View Model:

ViewModel classes are used to store the data even the configuration changes like rotating screen.Its purpose is to hold and manage the UI-related data. Moreover, its main function is to maintain the integrity and allows data to service during configuration changes like screen rotations.

 RecyclerView: 

Multiple notes can be added at the same time. It maintains the list of various notes added and updated. The RecyclerView has the ability to reuse its views. The same property is used in this application.

	LiveData: 

It is used to handle data in a lifecycle-aware fashion. Keeping the data displayed in a UI in sync with the data stored in a database. Here the LiveData is useful in deleting or updating the note.

	Room Database: 

It is used as a local data storage in android applications. The Room Database class uses the DAO to issue queries to the SQL database. In this app, the notes added and the updation done are stored.

<b>Future scope:</b>

The important notes can also be pinned to the home screen for easy and quick access. The app can be easily synchronized with all devices. Multiple users can edit at the same time as more than one user can access the documents and can comment on them. Hence, it can be collaborative. A feature of adding files, multimedia, and recordings can also be added. To make it more user-friendly we can give the user a choice of fonts or use a stylus with a tablet.

