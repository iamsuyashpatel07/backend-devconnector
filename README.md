# Preview

[Developer Valley](https://youtu.be/l8RxqUC9G6M)

# Setup

```cmd
git clone https://github.com/iamsuyashpatel07/social-media-app.git
cd social-media-app
yarn
cd client
yarn
```

### Add your credentials

**_Navigate_** to `$Root\social-media-app\config\default.json` and add the following

```JavaScript
{
  "mongoURI": "Your_Database_URL",
  "jwtSecret": "my_secret_token",
  "githubClientId": "Your_Github_ClientID",
  "githubSecret": "Your_Github_Secret_KEY"
}

```

### Run

```
$Root\social-media-app> yarn run application
```
