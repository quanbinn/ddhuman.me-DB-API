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

## Reference

1. [Accounts.createUser(options, [callback])](https://docs.meteor.com/api/passwords.html#Accounts-createUser)
2. [Adding user accounts](https://www.meteor.com/tutorials/blaze/adding-user-accounts)
