# Kanban-Board
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)


## Description
  Want to an app that uses visual tools to manage work to improve efficiency and collaboration? Then look no further! Kanban-Board allows you to easily and securely create todo notes for specific users and to update the status of the todos when they are in progress and finished.

## Usage
```md
AS A registered user

I WANT to authenticate using JSON Web Tokens (JWT)

SO THAT I can securely access and manage my tasks on the Kanban board
```
```md
GIVEN a login page with form inputs for username and password

WHEN I enter my valid username and password

THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page

WHEN I enter an invalid username or password

THEN I am presented with an error message indicating that the credentials are incorrect

WHEN I successfully log in

THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests

WHEN I log out

THEN the JWT is removed from the client's local storage and I am redirected to the login page

WHEN I try to access the Kanban board page without being authenticated

THEN I am redirected to the login page

WHEN I remain inactive for a defined period

THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action
```
![kanbanboard1](https://github.com/user-attachments/assets/c0858cbf-fd3d-41bb-b15c-78e93ca22549)

![kanbanboard2](https://github.com/user-attachments/assets/c1d2a84e-52bc-4dde-983f-1447ecc8eb8a)

![kanbanboard3](https://github.com/user-attachments/assets/062520e4-7008-45ee-a6f4-4eb78dd53a6e)

![kanbanboard4](https://github.com/user-attachments/assets/1b834494-a446-4828-b9fc-a380cceb3d02)

![kanbanboard5](https://github.com/user-attachments/assets/0070007c-58cf-4f71-a8bf-03e7d10dbf94)

![kanbanboard6](https://github.com/user-attachments/assets/1a5e036e-ab30-466e-8ff1-565724ded59f)

![kanbanboard7](https://github.com/user-attachments/assets/63c631b3-c874-468e-bfd6-20942ea247e1)

This web application has been deployed using Render and is viewable by going to this link: https://kanban-board-201c.onrender.com/

Note* In order to use the web app you will have to use one of the following accounts to securely log in using JWT:

Username: JollyGuru
Password: password

Username: SunnyScribe
Password: password

Username: RadiantComet
Password: password

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contributions
  Users can contribute to this project by allowing for the creation of new accounts. Currently you are only able to log in using one of the 3 premade accounts. 

## Tests
N/a

## Contact Information
Github Username: andrewsoper1
Email Address: soper.andrew6@gmail.com




