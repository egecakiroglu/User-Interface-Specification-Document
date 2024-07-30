User-Interface-Specification-Document
======================================

This is a specificaiton document for a user management document.

This screen consists of three parts : 

1. Header(Top)
2. Current users part(Left)
3. New user part(Right)


## Header

This is part is a header that lies in the top of the page, starting from left most side of the page and ending in right most side.

It includes 3 UI components (from left to right) : 

- A New User button : When clicked the New User part(explained below) on the right of the page should appear.

- A Hide Disabled User checkbox : When checked not enabled users in the table on the Current Users part(explained below) of the page should be hidden.

- A Save User button : After New User part is opened and fields are filled, when this button pressed a new user should be added to the table.



## Current Users 

In the left half of the page there shall be a table of current users with the following fields:
- ID

- User Name

- Email

- Enabled

The table should be properly margined with left of the page and the top header. 



## New Users

This part is in the right half of the page and is initially hidden.It is shown when New User button on the header is clicked.

It has a caption : New User

After the caption there are Input Fields that are needed to add a new user. Fields are as follows:

- UserName (String input field)

- Display Name (String input field)

- Phone (Integer input field)

- Email (String input field)

- User Roles (Selection among 3 roles : Guest, Admin, Super Admin )

- Enabled (Checkbox)


