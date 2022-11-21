# <a href='https://github.com/purpleblueslime/Yae-bot'>Yae-bot</a>
<img src='https://user-images.githubusercontent.com/84064124/202840888-c94ee869-dcf9-4f05-a770-57c9ef65addf.png' width=120 />
Claim genshin <a href='https://www.hoyolab.com/'><b>hoyo</b></a> dailies without even blinking!

## Getting started?

### Create your own <a href='https://github.com/purpleblueslime/Yae-bot/generate'>`Yae-bot`</a>

### Get cookie
<b>></b> Login to <a href='https://www.hoyolab.com/'><b>`hoyolab`</b></a>~<br>
<b>></b> Open developer window using `F12`.<br>
<b>></b> Select application tab and then cookies tab.<br>
<b>></b> From there copy `ltoken` and `ltuid`.

### Set cookie as envs
<b>></b> Open <a href='https://github.com/purpleblueslime/yae-bot/settings/secrets/actions'><b>`./settings/secrets/actions`</b></a> of your Yae-bot!<br>
<b>></b> Create a new secret `COOKIE` with values you copied from <a href='https://www.hoyolab.com/'><b>`hoyolab`</b></a>.<br>
<b>></b> New secret `COOKIE` should look like `ltoken=value;ltuid=value`. *value being values of each ltoken and ltuid*.

## and..thats it!!
<b>Now a cron should run everyday at 1am that'll claim your genshin hoyo dailies using your cookies :3</b>
