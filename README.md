# C01Lab3
## Table of Content
- [Objective](#objective)
- [Requirement](#requirement)
- [How to run](#how-to-run)
- [Features](#features)
### Objective
- Understand general backend development basics
- Get familiar with NoSQL
- Build a basic backend based on <a href=https://github.com/ArmandoRJr/c01w24lab3> Create Your first MERN App - Part 2 </a>
### Requirement 
- Please check <a href=https://github.com/ArmandoRJr/c01w24lab3#pre> here </a>
### How to run
- After cloning the repository, navigate to `quirknotes/backend` Directory. Open terminal in the directory and run the following command
```shell
npm install
npm run dev
```
- Open another terminal, navigate to `quirknotes/backend`, run the following command 
```shell
mkdir data\db
```
- Then run
```shell
"C:\Program Files\MongoDB\Server\7.0\bin\mongod.exe" --dbpath=.\data\db
```
- or if you have set up `monogd` path
```shell
mongod --dbpath=.\data\db
```
- Open another terminal and navigate to `quirknotes/frontend/src`
- Run the following command
```shell
npm install
npm run start
```
- Wait some time until you see pop-up tab in browser with `http://localhost:3000/`
- Then you can play with this note!
### Features
- This application served to be a note keeper and implement missing features on <a href=https://github.com/ArmandoRJr/c01w24lab3?tab=readme-ov-file#task> here </a> 
    1. Update note by clicking on `Edit Note` button and add information on the dialog block
    2. Delete note by clicking on `Delete Note` button
    3. Delete all note by clicking on `Delete All Note`