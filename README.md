# node-refresh-token
Implement Refresh Token Authentication Using Node and JWT

Clone the repository and switch to the project directory.

Install dependencies using ```npm install``` command then run the code using following command.

```node app.js```

Give following API calls to check the working.

```/login```

post data => 

```
{
	"email": "shahid@codeforgeek.com",
	"name": "Shahid"
}
```

```/secure```

in headers provide,

```x-access-header=access token from the previous API```
