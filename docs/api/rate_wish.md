# Rate Wish

Rate a wish
accessible with */rate_wish* path

## Description
Required Fields:

1. user_name : the user the is adding the wish
2. wish_id : the wish to rate
3. rating : the rating to give (1-5)

## example
example request:
```
{
	"user_name" : "JohnDoe123",
	"wish_id" : "1133223523b234d",
	"rating" : 4.1
}

```

response:
```
{
	"message" : "success",	
	"success" : true
}
```
