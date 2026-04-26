# Mini Java Project: Patient Management System

This is a small console-based Java project for managing patient records in a clinic.

## Features
- Register a patient (name, age, disease/concern)
- View all patients
- Mark a patient as visited

## Run
From the project root:

```bash
javac -d out src/Main.java
java -cp out Main
```

## Example Flow
1. Register patient: Name `John`, Age `30`, Concern `Fever`
2. Register patient: Name `Asha`, Age `25`, Concern `Headache`
3. Mark patient 1 as visited
4. View updated patient list
