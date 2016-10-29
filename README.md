## silex-twig-hello-world

#### Installation

**Step 1** - Install node dependencies

```
npm install
```

**Step 2** - Install php dependencies

```
curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer
composer install
```

**Step 3** - Build & watch sass and js

```
gulp dev
```

**Step 4** - Run server

```
./script/server
```

**Step 5** - Visit http://localhost:8080 and Enjoy!

#### Troubleshooting

If you get an error something along the lines of `It is not safe to rely on the system's timezone settings` - add your timezone to `/private/etc/php.ini` and re-run the server script.