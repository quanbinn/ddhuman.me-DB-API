# createUser

```javascript
function createUser(username, password) {
	if (db.users.find({"username":username})["username"] == username) {
		alert("The username already exists. Please use a different username.");
	} else {
		db.users.insert({
			username: username;
			password: password;
			createdAt: new Date();
		})
	}
}
```

