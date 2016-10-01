# How It Works

As stated before, the goal of OpenWish is wish sharing. 
In the OpenWish API, each user has basically two calls:

1. Adding a wish - a user can add a wish to the DB
2. Reading a wish - a user can read anothers user's wish
3. Rating a wish - a user can rate a wish that was read

There are two limitations:

1. Wish Reading - A user can only read as many wishes as s/he has added
This is meant to encourage wish adding
2. Wish Adding - A user's abillity to add wishes is limited by the ratings he receives on his wishes
This is meant to limit spam wishes

## How it will be implemented in the android app

The android app will have a quick "add & read" feeling: 
A user will only be able to add wishes, and every time he does so, 
he'll receive a wish - so the app will have a short "reward loop" from adding wishes,
and won't used as an analytics tool
