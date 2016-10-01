# Get Wishes

retrives all the wishes the user can get
accessible with */get_wishes* path

## Description
Required Fields:

1. user_name : the user the is adding the wish

Optional Fields:

1. created_wishes : get the created wish of the user
2. read_wishes: get the wishes read by the user

if none of these are specified, both are assumed true

## example
example request:
```
{
	"user_name" : "JohnDoe123",
	"created_wishes" : true,
	"read_wishes" : true
}

```

response:
```
{
	"message" : "success",
	"data" : {
		"created_wishes" : [
			"11292523abcde",
			"6756b76abbcef123"
		],
		"read_wishes" : [
			"2234234234bdd"
		]
	},
	"success" : true
}
```
