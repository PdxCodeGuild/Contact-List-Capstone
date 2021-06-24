# Contact List Capstone


## Project Overview

ContactListCapstone is a Django application for managing a list of contacts. It will include a user system for registering, logging in, and logging out. Each use will only see their own list of contacts.

**Libraries Used**:
- [Django](https://www.djangoproject.com/)
- [Pillow](https://pillow.readthedocs.io/en/stable/)
- [Materialize](https://materializecss.com/)


## Features

- User System
  - Register
  - Login
  - Logout
- Contact List
  - List of contacts
  - Create contact
  - Edit contact
  - Delete contact

## Data Model

**City**
- name (CharField)


**Contact**
- name (CharField)
- profile_image (ImageField)
- email (EmailField)
- birthday (DateField)
- organ_donor (BooleanField)
- city (ForeignKey to City)
- user (ForeignKey to User)

**User** (built-in)


## Schedule

### Week 1

- Create models, upload dummy data using Faker
- Create user system - register, login, logout

### Week 2

- Show a list of contacts on the front page
- Create a contact
- Delete a contact

### Week 3
- Edit a contact
- Styling




<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

## Markdown Examples


![cat image](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e6/Eva_and_Franco_Mattes%2C_Ceiling_Cat.jpg/320px-Eva_and_Franco_Mattes%2C_Ceiling_Cat.jpg)

------

[markdown table generator](https://www.tablesgenerator.com/markdown_tables)

| id | name    |
|----|---------|
| 1  | Apples  |
| 2  | Bananas |
| 3  | Pears   |

*italic*
**bold**
***bold and italic***
~~stikethrough~~

> Quote

- Apples
- Bananas
- Pears

1. Apples
2. Bananas
3. Pears

