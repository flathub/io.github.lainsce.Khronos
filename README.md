# Khronos

___Log the time it took to do tasks___

Start logging any task's time to completion, with the ability to stop the timer at any moment, with notifications for longer task sessions.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub io.github.lainsce.Khronos
flatpak run io.github.lainsce.Khronos
```

## Building

```
git clone git@github.com:flathub/io.github.lainsce.Khronos.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.lainsce.Khronos.json
```
