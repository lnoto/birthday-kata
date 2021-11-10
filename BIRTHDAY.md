# Birthday Kata
As you’re a very friendly person, you would like to send a birthday note to all friends that you have. 
But you have a lot of friends and you are a bit lazy, it may take some time to write all the notes by hand.

The good news is that computers can do it automatically for you.

Imagine you have a flat file with all your friends :

```
last_name, first_name, date_of_birth, email
Doe, John, 1982/10/08, john.doe@foobar.com
Ann, Mary, 1975/09/11, mary.ann@foobar.com
```

And you want to send them a happy birthday email on their birthday:

```
Subject: Happy birthday!

Happy birthday, dear <first_name>!
```


Implement a solution that sends the message to the friends that have a birthday today.

## TIP
We suggest starting from what you think is the core of the application.
