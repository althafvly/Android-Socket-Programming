# Client-Server Communication app

This repository have two projects. It makes use of Socket Programming in android to demonstrate communication between different applications on different devices.

## Installation
* Clone this repository and open client and server in different window on **Android Studio**
  ```bash
   git clone git@github.com:althafvly/Android-Socket-Programming.git
  ```
### On the server-side of project
  * Change the SERVER_PORT of MainActivity to host in specific PORT
    ```java
    public static final int SERVER_PORT = 5050;
    ```

### On the client-side of project
  * Change the SERVER_IP and SERVER_PORT of MainActivity to device's IP and hosted PORT
    ```java
    public static final int SERVER_PORT = 5050;
    public static final String SERVER_IP = "192.168.100.1";
    ```

## Usage
* Connect both device to the same network
* Click on the start server button of the server app
* Click the connect to server button on the Client-side app 
* You can now send and receive messages between both apps

## Maintainers
This project is mantained by:
* [Wisdom Praise](http://github.com/wizzywit)
* [Diretnan Domnan](http://github.com/deven96)
* [althafvly](http://github.com/althafvly)

## Contributing
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -m 'Add some feature')
4. Push your branch (git push origin my-new-feature)
5. Create a new Pull Request
