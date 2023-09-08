#gametools
## installation
```bash
curl -s https://api.github.com/repos/RusNor/Ported-version-of-MangoHud-and-vkBasalt/releases/latest | grep "install_gmv_utils_v" | cut -d : -f 2,3 | tr -d \" | wget -qi - || chmod +x $HOME/install_gmv_utils_v* && sh install_gmv_utils_v*
```
## How to use?

You can set your own value to limit fps 

```bash
FPS=60 gmv
```
Force use opengl

```bash
OPENGL=1 gmv
```

If you use Wine, all you have to do is enter the command gmv in the terminal:

```bash
gmv wine name.exe
```

or just enter a command for the test:

```bash
gmv
```

If you use Steam, insert the following command in the game properties:

```bash
gmv %command%
```

![gmv_2](https://user-images.githubusercontent.com/85447162/174639828-cb69b4f2-2f96-4eff-b8c4-4bb724efc643.png)

## About

discord channel welcome [Click](https://discord.gg/37FrGUpDEj)

