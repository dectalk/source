# Fonix DECtalk

Welcome to DECtalk... or a copy of it, found from [_@datajake1999_'s webserver](from a webserver off [grossgang.com](http://grossgang.com/tts/dectalk%20software%20and%20manual/Ad%202.zip))

This repository aims to do something with the code.
Whatever it is, I don't know.

## Building

**This does not work yet.**
I'm trying, but there's too many errors.
Hop onto Discord or send a pull request!

```sh
# Stuff you need!
sudo apt install libgtk2.0-dev

# Autoreconf... dunno
autoreconf

# Something about having to use `-fPIC`
CC='gcc -fPIC -g -O2' ./configure

# Make
make
```

## Branches

- For the built version of DECtalk on an older version of Linux and GCC (x86), see the [`linux-compile`](https://github.com/dectalk/source/tree/linux-compile) branch.
- For the original DECtalk, see the `v5-beta` tag
    - [Why `v5-beta`?](https://old.reddit.com/r/DecTalk/comments/ilbuxj/dectalk_for_linux/g4jo688/)
- For the ongoing efforts to improve DECtalk, see the `master` branch, as well as any other branches developers may be using at the moment.

## Chatter

You can help discuss the project on:

- GitHub Issues
- Discord (https://discordapp.com/invite/wHgdmf4)
    - Make sure very _very_ important questions are on GitHub issues instead,
      so they're not lost to time like Yahoo Answers.

## Legacy

This code is probably owned by some holding company somewhere now.
If you really want to give thanks, try one of these people:

`/src/samples/speak/TEAM03.BMP`  
![The DECtalk Team](.github/TEAM03.png)

## Thanks

Who                 | Why
------------------- | ------------
@datajake1999       | Hosting the original source code on their webserver

