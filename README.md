## About The Project

This is a live chat app using larvel pusher,echo plus vue.js.

### important note :

have used built in laravel features :Laravel pusher and Laravel Echo
for front-end i have used vue.js for simple ui for testing proposr ,
i have kept the .env file for the pusher keys setup

### Installation

1. Clone this repo
2. Install Composer packages
    ```sh
    composer install
    ```
3. Install NPM packages
    ```sh
    npm install
    ```
5- create the db 
```called 
"live_chat" as in the .env file
```
6. Initilise the database
    ```sh
    php artisan migrate
    ```
7. Compile the webpages and run it
    ```sh
    npm run dev
    php artisan serve
    ```

## Usage

Go to http://127.0.0.1:8000/, register a couple of users and start chatting!
