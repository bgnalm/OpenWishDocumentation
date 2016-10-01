# Create User

adds a new user
accessible with */create_user* path

## Description
Required Fields:

1. user_name : the user the is adding the wish

## example
example request:
```
{
	"user_name" : "JohnDoe123",
}

```

response:
```
{
	"message" : "success",
	"data" : {
		"user_id" : "57eeab86ad775f586cd"
	},
	"success" : true
}
```
