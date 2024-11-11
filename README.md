# ByteBinderDB
- This is a database very similar to SQLite.
- Built on B+ tree data structure, written in C
# Available Commands
- .btree : shows the leaf node structure of tree
- .constants : such as no. of cells, node size (bytes)
- .exit : exit the DB shell
- insert id username email
- select : output all the rows
- select id : output only id(th) row
- update id username email : updates old username and email with the new ones for the given id
# How to Run
- First compile the file as ```gcc FinalDB.c -o finaldb.exe```
- Open the exe file along with db file as an argument ```./finaldb.exe test.db```
- Now the DB shell is opened, and is available to take commands
- For exit ```.exit```
