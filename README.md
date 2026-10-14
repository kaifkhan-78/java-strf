# Student Registration Form

A Java Swing desktop form demonstrating text fields, radio buttons, checkboxes, event handling, and basic required-field validation.

## Requirements

- JDK 17 or later

## Run

```bash
javac StudentRegistration.java
java StudentRegistration
```

## Current validation

- Student name and roll number are required
- A gender option must be selected
- Branch is required
- Terms must be accepted
- Reset clears the form

## Important scope note

The form currently validates data in the UI and displays a confirmation dialog; it does **not** save registrations to a database or provide login/authentication. For a production registration system, add server-side validation, persistent storage, duplicate-roll-number checks, and privacy-conscious handling of student data.
