# Podcast
Symfony create podcast and upload it

Config in your .env

```
MAILER_DSN=gmail://email:password@localhost

DATABASE_URL="mysql://root:password@127.0.0.1:3306/podcast?serverVersion=5.7"
```

Then run server with 
```
symfony server:start (or server:stop to stop it)
```