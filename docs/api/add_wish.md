# Add Wish

adds a wish to the server.
accessible with */add_wish* path

## Description
Required Fields:

1. user_name : the user the is adding the wish

2. wish: an object describing the wish

3. wish.text - each wish has to have text


Optional Fields:

1. wish.optional : all the optional metadata about the wish

## example
example request:
```
{
	"user_name" : "JohnDoe123",
	"wish" : {
		"text" : "I wish i could know where traffic jams are going to be",
		"optional" : {
			"city" : "London",
			"recurring" : true,
			"age" : 30
		}
	}
}

```

response:
```
{
	"message" : "success",
	"data" : {
		"wish_id" : "57eeab86775f586cd"
	},
	"success" : true
}
```
