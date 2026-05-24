# fzn (fzf notes)
`fzn` is a minimalist, lightning-fast POSIX shell script for managing plain-text Markdown notes. 

![](./demo/pizdec.webp?raw=true)

---

## features:
* **deep directory support** – interactive folder selection when creating notes, allowing you to easily categorize your thought-base.
* **placeholders** – automatic fallback to standard timestamps (`YYYY-MM-DD_HH-MM-SS`) if you don't want type a title.
* **lightweight** – under 100 lines of highly readable with a litle dependencies.

---

## setup guide:

download, give him permission:
```sh
git clone https://github.com/zyuzya1984/fzn.git
cd fzn/
chmod +x fzn
```
(btw, make sure u create a folder for having ur notes)

'''sh
mkdir ~/notes
```

---

## requirements:
* **fzf**
* **POSIX-compliant shell**

---

## configuration:

the script adapts dynamically based on your environment variables. u can set these in your **.bashrc**, **.zshrc** and etc...
```sh
export TERMINAL=".."               # terminal
export EDITOR="..."               # ur editor
```
---

## usage:

simply run the script:

```sh
./fzn
```

---

## credits:
[breadonpenguins](https://github.com/BreadOnPenguins/scripts/blob/master/shortcuts-menus/notes) – an original concept of this script (thx u ^_^)

---

## License

[MIT](./LICENSE)

