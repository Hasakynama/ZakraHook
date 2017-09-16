# ZakraHook

#### Attention! You need lua and xdo to compile ZakraHook. Please don't skip this!

__Ubuntu-Based / Debian:__
```bash
sudo apt-get install cmake g++ gdb git libsdl2-dev zlib1g-dev liblua5.3 libxdo-dev patchelf
```
__Arch:__
```bash
sudo pacman -S base-devel cmake gdb git sdl2 lua xdotool patchelf
```
__Fedora:__
```bash
sudo dnf install cmake gcc-c++ gdb git libstdc++-static mesa-libGL-devel SDL2-devel zlib-devel lua-devel libX11-devel libxdo-devel patchelf
```

__Gentoo:__
```bash
sudo emerge cmake dev-vcs/git gdb libsdl2 mesa lua xdotool patchelf
```
===================

#### Download ZakraHook:

```bash
git clone --recursive https://github.com/Hasakynama/ZakraHook
```

```bash
cd ZakraHook
```

===================


#### Compile with build script

You can build easily with the included build script.
```bash
./build
```
You can later update with 
```bash
./update
```

## Injecting

First of all, make sure CSGO is open, it doesn't matter whether you're in game or not. However, it is not recommended to inject while CSGO is loading into a map. 

Navigate to the directory where ZakraHook was built if you haven't ready.

```bash
cd ZakraHook
```

Now, you can inject the hack with the `load` script

```bash
./load
```

You might be prompted to enter in your password, this is because the injection script requires root access.

The text printed out during injection is not important. 

If the injection was successful you'll see a message at the bottom saying `Successfully injected!`, however, if the message says `Injection failed`, then you've most likely done something wrong.


## Using the hack

Now that ZakraHook has been injected into the game, press <kbd>Insert</kbd> on your keyboard to open the hack menu (<kbd>ALT</kbd>+<kbd>I</kbd> if you're using a laptop).
