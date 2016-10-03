# Read Wish

Reads a wish. 
accessible with */read_wish* path

## Description
Required Fields:

1. user_name : the user the is adding the wish

Optional Fields:
(In development):

1. In text: read a wish with the text field that contains these words
2. field : read a wish that has a specific field
3. field value: read a wish that has a specific field value

if none of these are specified, both are assumed true

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
	"success" : true
}
```
