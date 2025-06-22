*&---------------------------------------------------------------------*
*& Report Z_ABAP_FIRST_PROGRAM
*&---------------------------------------------------------------------*
*&
*&---------------------------------------------------------------------*
REPORT Z_ABAP_FIRST_PROGRAM NO STANDARD PAGE HEADING.

*Write keyword is used to display the statements and every statement is end with period '.'
WRITE 'My First ABAP Program'.

*To display the statement to the next line use '/' forward slash.
WRITE / 'In SAP S/4 HANA'.

*We can pass more than one statement or variable by specifying : after write keyword
WRITE :/ 'My first ABAP Program', / 'IN SAP S/4 HANA' .

WRITE :/.

*Specifying position in write statement
WRITE :/5 'Name', 20 'Role', 35 'Email ID'.
WRITE :/5 'Aurthur', 20 'FRIORI', 35 'aurthur@gmail.com'.
WRITE :/5 'Vasuki', 20 'ABAP', 35 'vasuki@gmail.com'.
WRITE :/5 'Mia', 20 'Basis', 35 'mia@gmail.com'.

WRITE :/.

*Underline each statement by 'uline'
uline.
WRITE :/5 'Name', 20 'Role', 35 'Email ID'.
uline.
WRITE :/5 'Aurthur', 20 'FRIORI', 35 'aurthur@gmail.com'.
uline.
WRITE :/5 'Vasuki', 20 'ABAP', 35 'vasuki@gmail.com'.
uline.
WRITE :/5 'Mia', 20 'Basis', 35 'mia@gmail.com'.
uline.

WRITE :/.

*To draw vertical line by '|'
uline.
WRITE :/5 'Name', '|', 20 'Role', '|', 35 'Email ID', 60 '|'.
uline.

WRITE :/.

*Or by using sy-vline
uline.
WRITE :/5 'Name', 20 sy-vline, 'Role', 35 sy-vline, 'Email ID', 60 sy-vline.
uline.
WRITE :/5 'Aurthur', 20 sy-vline, 'FRIORI', 35 sy-vline, 'aurthur@gmail.com', 60 sy-vline.
uline.
WRITE :/5 'Vasuki', 20 sy-vline, 'ABAP', 35 sy-vline, 'vasuki@gmail.com', 60 sy-vline.
uline.
WRITE :/5 'Mia', 20 sy-vline, 'Basis', 35 sy-vline, 'mia@gmail.com', 60 sy-vline.
uline.

*Add Colors
uline.
WRITE :/5 'Name' COLOR 4 , 20 sy-vline, 'Role' COLOR 3 Intensified ON, 35 sy-vline, 'Email ID' COLOR 6, 60 sy-vline.
uline.
WRITE :/5 'Aurthur' COLOR 5 INVERSE ON, 20 sy-vline, 'FRIORI' COLOR 2, 35 sy-vline, 'aurthur@gmail.com' COLOR 1 INTENSIFIED OFF, 60 sy-vline.
uline.

WRITE :/.

*Apply single color for more than one statement
FORMAT COLOR 7.
WRITE / 'End of Records'.
WRITE / 'End of Report'.
FORMAT COLOR OFF.
