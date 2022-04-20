dwm slstatus can make dwm have a very beautiful status bar.

![slstatus](https://user-images.githubusercontent.com/81478335/164266631-f37d43e5-90aa-4631-9817-af2e57d5dc11.png)

```
$ git clone https://github.com/askfiy/slstatus
$ cd slstatus
$ sudo make clean install
```

You should use it with [askfiy/dwm](https://github.com/askfiy/dwm).

Add to ~/.xinitrc or autostart.sh:

```
slstatus &
```

If you want to modify some configuration, you can edit [config.h](./config.h)
