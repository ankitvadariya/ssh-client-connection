# SSH client connection over http

SSH client connection library can be use when you don't want to share your server's password but you need to give access to user / developer.

##### To Do : 
  1. git clone https://github.com/ankitvadariya/ssh-client-connection.git
  2. cd ssh-client-connection
  3. npm install or yarn install
  4. add server detail in server.js
```
		  host: "YOUR_HOST",
		  port: PORT, // Generally 22 but some server have diffrent port for security Reson
		  username: "USER", // any user
		  password: "PASSWORD" // Set password or use PrivateKey
		  privateKey: require("fs").readFileSync("PATH OF KEY FILE")
```
  5. yarn start

- I would like to recommand SSL if you are going to use on live envirment.
- Please use it with your own risk.
- feel free to contact me: iam@ankitvadariya.com
