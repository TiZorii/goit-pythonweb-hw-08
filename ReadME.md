# Topic 8. Homework

The goal of this assignment is to create a REST API for storing and managing
contacts. The API should be built using the FastAPI framework and utilize
SQLAlchemy for database management.

---

## Technical Description of the Assignment

### 1. Contacts

To store the contacts in your system, you need to organize a database that will
contain all the necessary information.

This information should include:

- **First Name**
- **Last Name**
- **Email Address**
- **Phone Number**
- **Birthday**
- **Additional Information** (optional)

---

### 2. API

The API you develop should support basic data operations. Below is a list of
actions your API should be able to perform:

- Create a new contact
- Retrieve a list of all contacts
- Retrieve a single contact by its identifier
- Update an existing contact
- Delete a contact

---

### 3. CRUD API

In addition to basic CRUD functionality, the API should also have the following
features:

- Contacts should be searchable by first name, last name, or email address
  (using query parameters).
- The API should be able to retrieve a list of contacts with birthdays in the
  next 7 days.

---
