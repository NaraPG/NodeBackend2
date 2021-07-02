## Backend Node.js

## This repository
> The project of this course manage the platzi data. We create an API REST to consult and modify data system, displaying data in cloud services.

## Introduction
#### What is Node.js?
> Node.js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

#### What is nodemon?
> nodemon is a tool that helps develop node. js based applications by automatically restarting the node application when file changes in the directory are detected.

## Examples of Concepts
> - MongoDB
>   * Create
>   * Read
>   * Update
>   * Delete
> - `Streams`: Streams are one of the fundamental concepts that power Node.js applications. They are data-handling method and are used to read or write input into output sequentially.
>     * Writable streams are an abstraction for a destination to which data is written.
>     * Readable streams are an abstraction for a source from which data is consumed.
> - `Websockets`: It is a stateful protocol, which means the connection between client and server will keep alive until it is terminated by either party.

## More information
> [General content](https://github.com/JasanHdz/backendnodejs/tree/master/notes#tabla-de-contenido)


> [EventEmitter]:(https://github.com/JasanHdz/backendnodejs/tree/master/notes#event-emiter)


> [Streams](https://nodejs.org/api/stream.html#stream_readable_streams)


## Differences between Node.js and JavaScript
> - NodeJS :
>    NodeJS is a cross-platform and opensource Javascript runtime environment that allows the javascript to be run on the server-side. Nodejs allows Javascript 
> code to run outside the browser. Nodejs comes with a lot of modules and mostly used in web development.

> - JavaScript :
> Javascript is a Scripting language. It is mostly abbreviated as JS. It can be said that Javascript is the updated version of the ECMA script. Javascript is a high-level programming language that uses the concept of Oops but it is based on prototype inheritance.

<img src="https://user-images.githubusercontent.com/79294934/124240522-6f506000-dae0-11eb-93c3-22da37ff423d.png"></img>


## Dependencies
> - Install [VS Code](https://code.visualstudio.com/download)
> - Install [Node.js](https://nodejs.org/en/)
> - Install nodemon (Optional)
>   * Cloning with git or by using npm (the recommended way):
> ```
> npm install -g nodemon
> ```
>   * You can also install nodemon as a development dependency:
>   ```
>   npm install --save-dev nodemon
>   ```

## Run Code
> - Use `npm i` to install the project dependencies
> - For Windows use the command `cd [path]` and `npx nodemon [script]` to run the project automatically
> - MongoDB Atlas
> 1- Create mongo database: I used the [mongodb altas](https://www.mongodb.com/cloud/atlas) platform for creating and managing one.Later you will need to create a user/password in order to connect the server with the DB.
> 
> 2- Create `.env` in the root path `/` file and your variables

```
DB_NAME=core-xyz.gcp.mongodb.net
DB_USER=db_user_value
DB_PASSWORD=db_password_value
```

## Technologies
> - JavaScript

_Created by Nara Peña Gámez._
