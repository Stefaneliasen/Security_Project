# Security_Project
### Oliver Scholz Lønning,
### Elias Zinabidine Laghouila, 
### Stefan Schou Eliasen 
### Mathias Bartels Jensenius

## Healthy security for a regular project

Our project is supposed to show a good way to handle and execute different tasks in a standard:

`Database <-> Backend -> * JSON REQUESTS * <-  Frontend` relationship.

We will use the current points, build on another idea of a subject for a website:

* **SQL injection preventions**
* **Hashing of passwords**
* **Crypto ciphering of user details**
* **Stronger security for register credentials in form of identity keys**
* **Cookie authorization**
* **CORS**


### Overview of the projects sturcture

The project has a shell of a Security_Project folder with a readme file.

The project also consists of two submodules:

Client_Security git repo for frontend.

Server_Security git repo for backend.

## How to clone the repo

Run:

``` git clone --recurse-submodules https://github.com/HawkDon/Security_Project.git ```

This will clone the repo and the submodule folders that is in this repo.

## To stage commits
Assume you are in one of the sub module folders(Client or Server). Run the usual:

```
git add .
git commit -m "message"
git push
```
Afterwards go out to the root(Project_Security) and run the usual:

```
git add .
git commit -m "message"
git push
```

This will update the shell on github aswell.

## Client

## To run the first time:

```
npm install
npm start
```
