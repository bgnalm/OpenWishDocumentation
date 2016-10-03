# Time Left

Gets in how much time the user will be able to do stuff
accessible with */time_left* path

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
		"can_read" : true,
		"can_post" : false,
		"next_post" : 34 (Seconds!)
	},
	"success" : true
}
```
