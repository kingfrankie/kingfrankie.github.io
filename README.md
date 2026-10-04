GitHub Pages user site for a personal Tesla Fleet API app.

- `/.well-known/appspecific/com.tesla.3p.public-key.pem`: EC prime256v1 **public** key (the private key never leaves the bot's machine)
- `/callback/`: OAuth redirect page. It shows the authorization code so it can be pasted to the bot and sends nothing anywhere.
- `.nojekyll` so GitHub Pages serves the `.well-known` dot-directory.
