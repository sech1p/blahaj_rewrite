# 🦈 Blahaj Rewrite

This repository contains rewrite of [blahaj](https://github.com/sech1p/blahaj) from TypeScript to C++.

I planned to rewrite blahaj to some compiled language from [some time](https://github.com/users/sech1p/projects/4?pane=issue&itemId=78622173). And there we go, you can see future version of blahaj here.

## ❓ Why C++ instead of Rust?

There are some reasons, why I use C++ instead of Rust, the main reason is that I don't know Rust, I never have to write smth in this language.

Second reason is strictly related to first reason, I just preffer writting in C++ which I know. Just all.

Remember that is this only concept, everything can be changed during development.

## ❓ FAQ

- This blahaj rewrite will be exactly same as original blahaj?

Yes, of course, I didn't have plans to make dramatical changes, all of syntax used in blahaj application will be the same as in original

- When rewrite will be released?

Honestly, i don't know, I don't always have time or mood to write code. Actually, I want to finish everything in OG blahaj

- Will this rewrite replace OG blahaj?

I'm not sure if i should keep legacy version of blahaj and rewrite in the same time (e.g. maintaining Python 2 and 3 in same time wasn't a good idea)

I will think about this, but now it's kinda far to make a verdict

## 🔧 Building

You must have installed [meson](https://mesonbuild.com), and C++ compiler (gcc or clang)

```sh
$ meson build
$ cd build
$ ninja
```

Now blahaj is builded into `blahaj` executable in `build/` folder

## 🗒️ License

`blahaj` (aka blahaj_rewrite) is licensed under [Apache-2.0](LICENSE) license.

All trademarks, logos and brand names are the property of their respective owners. All company, product and service names used in this website are for identification purposes only. Use of these names, trademarks and brands does not imply endorsement
