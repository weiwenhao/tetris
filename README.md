Tetris game using [nature](https://github.com/nature-lang/nature) (>0.5.0) programming language + [raylib](https://www.raylib.com) library, macos platform only!

![](https://raw.githubusercontent.com/weiwenhao/pictures/main/20250425001515329.png)

### Build

1. install the https://github.com/nature-lang/nature nature compiler


2. build and get the main binary

```sh
nature build --ldflags '-framework IOKit -framework Cocoa' main.n
```

3. Run the main binary
```sh
. /main
```

### License
MIT

