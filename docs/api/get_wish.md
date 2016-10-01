# Get Wish

retrives a wish from the server
accessible with */get_wish* path

This call is only for getting wishes that are already accessible to the user

i.e wishes that were read by the user or created by the user

##  Request Description
Required Fields:

1. user_name : the user that is getting the wish

2. wish_id: the id of the wish

## Response Description

the response data field will contain the information about the wish

## example
example request:
```
{
	"user_name" : "JohnDoe123",
	"wish_id" : "364929ed87c807a8079f"
}

```

response:
```
{
	"message" : "success",
	"data" : {
		"text" : "I wish there were more clocks",
		"time_added" : 1474535225234.
		"user_name" : "DoeJohn321",
		"rating" : 1.1,
		"number_of_reads" : 52,
		"optiona" : {
			"coountry" : "France"
		}
	},
	"success" : true
}
```
