# Firebase Firestore Data Write Issue

This repository demonstrates a bug where a Firebase Firestore write operation appears successful (no errors) but doesn't actually persist the data in the database.  The solution is included to highlight potential causes and resolutions.

## Bug Description
The `firestoreBug.js` file contains code that attempts to write data to a Firestore collection.  Despite using the correct methods and syntax, the data does not appear in the database, and no errors are thrown. 

## Solution
The `firestoreBugSolution.js` file presents a revised approach. It addresses common causes such as incorrect security rules, missing imports or improper data structuring.