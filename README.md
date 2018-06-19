For Server Admin:
=================

1. Install MySQL Community Server from https://dev.mysql.com/downloads/installer/
2. On the Server configuration, add/create a 'User Account' to be used by the Program.
3. Start the Server.
4. Create a Database Schema and two tables; one for the Sender and the other for the Receiver.
5. Populate the Sender and the Receiver tables with columns that will be asked from the Program.
6. Reserve the first column of each table for the Control Number (or PR, whatever). 
7. The Control number identifies the docoment that is sent or received.

For Program users:
1. Install Java.
2. Run the Program jar.
3. Enter the Server configurations to access the database. Ask the Server admin.
4. Enter the table name used for the Sender Table in the database.
5. Do the same for the Receiver Table.

Using the Program:

Under the Tools Menu:

A. Sender Form:
1. Fill the required fields. Predefined texts can be inserted using the buttons to the right.
2. Enter Save location with 'png' extension. 
3. Select Submit button. The Program will update the database.
4. Only the first entry will be encoded on the QR image.
5. Embed the image to the document for printing.

B. Receiver Form:
1. Load the image from the computer to the program.
2. Fill in the required fields except for the Control Number.
3. The control number can be accessed using the button to the right.
4. Fill the control number.
5. Click Submit button. The Program will notify the database.

C. Document Tracker:
1. Enter the Control number of the document.
2. Two tabs will appear. The first one is the result from the Sender Table.
3. The second is from the Receiver table.
4. Entries not found on the Sender Table means that the same was not yet sent.
5. Entries not found on the Receiver Table means that the same was not yet received.

D. Generator Form:
This extra tool generates a customized QR code.

E. Reader Form:
This extra tool reads a custom QR code.

Bonus:
1. Clicking any QR image enlarges the same.




