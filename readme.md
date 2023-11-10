## Contacts - node.js

<a href="https://monosnap.com/file/SO7JcgmzUenhpjC7dTkIjrgGHcZafO" target="_blank">Screenshot:
Displaying the Entire Contact List</a>

<a href="https://monosnap.com/file/z1J2fYvrCZ2qyfLGoX1Ri3oLOcp1wp" target="_blank">Screenshot:
Retrieving a Contact by ID</a>

<a href="https://monosnap.com/file/fl5InpcqWr4ykv7t0cCcWUQbfp2qiH" target="_blank">Screenshot:
Adding a New Contact</a>

<a href="https://monosnap.com/file/ZROhGKzNmWMoExrs3wpUB5k7bTzCru" target="_blank">Screenshot:
Removing a Contact</a>

#### Display and Output the Entire Contact List as a Table:

bash

node index.js --action list

This command retrieves and displays the entire list of contacts in a table
format using console.table.

#### Retrieve a Contact by ID:

bash

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6

Use this command to fetch and display details of a contact by specifying its
unique ID.

#### Add a New Contact:

bash

node index.js --action add --name Mango --email mango@gmail.com --phone
322-22-22

This command adds a new contact with the name "Mango", email "mango@gmail.com",
and phone number "322-22-22" to your contact list.

#### Remove a Contact:

bash

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH

Use this command to delete a contact from your contact list by specifying the
contact's ID.
