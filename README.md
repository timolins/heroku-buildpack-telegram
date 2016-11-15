# DEPRECATED since the [official Bot API](https://core.telegram.org/bots/api/) has been released!

# heroku-buildpack-telegram
Heroku Buildpack for the [Telegram CLI](https://github.com/vysheng/tg).

This buildpack only works in combination with  [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi), so you can use [heroku-buildpack-apt](https://github.com/ddollar/heroku-buildpack-apt) with the following `Aptfile`:


```
libreadline-dev
libconfig-dev
libssl-dev
lua5.2
liblua5.2-dev
libevent-dev
make
```
After a successful build the `telegram-cli`command will be available globaly. You can try it out with `heroku run telegram-cli`.

