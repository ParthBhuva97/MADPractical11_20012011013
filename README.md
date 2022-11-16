# MADPractical11_20012011013

Study: SQlite Database, RecyclerView, Broadcast Receiver, Service, Notification, Custom Alert Dialog Box, Time Picker Dialog, AlarmManager

AIM: Create Note Android Application that can add Note, edit Note, delete Note, and set reminder date & time of note. By using Broadcast Receiver, AlarmManager set reminder of note. By using SQLite, store all notes data.

1. Create two Activities like MainActivity, NoteViewActivity according to below UI design.

2. Use RecyclerView Code from Practical-9 to display Note Data.

3. Use Broadcast Receiver, Time Picker Dialog, service & AlarmManager code from Practical-7

4. Create Note class with member variables like id, title, subTitle, Description, modifiedTime, reminderTime:Long, isReminderEnable:Boolean & create membor methods like getCurrentDateTime(), getMillis(), setReminder(), isValid(), getReminderText(), saveNote(), getHour(), getMinute(), calculateReminder() 

5. Create DatabaseHelper Class for SQlite with member methods like insertNote(), getNote(id), getAllNotes(), getNotesCount(), updateNote(), deleteNote().

6. Use Databinding in gradle file to easy way integrate xml into kotlin file

7. Use Material 3 design for UI

8. create class NotesData with companion object and it will store column name of table and create table query.

9. Create NoteViewActivity. It will show while reminder notification is turned up and user click on notification. It will also show when click on Note in recyclerView. After clicking on notification NoteViewActivity should be open with full description of that note. 

10. Note should be deleted by clicking on icon of Delete. Note should not be added if any one field of note is empty.

11. Some notes have reminder time so add reminder time in alarmManager with note id & it should be receive in broadcast receiver & in broadcast receiver notification should be generated with title & description of note.

12. If More than one notes have reminder time then notification should be displayed for each note separately.

13. Create Common Custom Dialog Box for add, edit note.

14. Create RecyclerView & its adapter to display all notes.

# Output : 

![image](https://user-images.githubusercontent.com/98973295/202262342-a63933bc-ea41-4170-b209-43ef531405d8.png)
![image](https://user-images.githubusercontent.com/98973295/202262353-32307b8f-0cc1-453a-938e-de928e1751e2.png)


![image](https://user-images.githubusercontent.com/98973295/202262382-f6fbe603-02c4-4253-a832-9c98149f900d.png)
![image](https://user-images.githubusercontent.com/98973295/202262404-4b4b876c-f933-492b-acd5-c8ef45c46d0d.png)


![image](https://user-images.githubusercontent.com/98973295/202262421-c749011d-7a98-4950-b651-6b79a369e1a3.png)


![image](https://user-images.githubusercontent.com/98973295/202262456-9a444a3c-734b-4d68-a374-ef1ce581cd62.png)







