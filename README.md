**NOTE**

This repository is not maintained. Please use [binch-go](https://github.com/tunz/binch-go) instead. I just rewrote this in Go since python is slow and keystone python library is not maintained well.

---

# a light BINary patCH tool
A light ELF binary patch tool in python urwid. It helps to patch a ELF binary in a few steps.

![capture](https://cloud.githubusercontent.com/assets/7830853/9346653/9d0fb980-465a-11e5-9908-541ae4c80492.png)

Now, it only supports x86, x86_64, and ARM(experimental).

## Usage

```
$ ./binch [binary name]
```

#### Shortcuts
```
g: Go to a specific address. (if not exists, jump to nearest address)
d: Remove a current line. (Fill with nop)
q: Quit.
s: Save a modified binary to a file.
enter: Modify a current line.
h: Modify hex bytes of a current line.
f: follow the address of jmp or call instructions.
```
