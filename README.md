# flatpak-lilbee

Flatpak repository for [lilbee](https://github.com/tobocop2/lilbee), served via GitHub Pages. Updated automatically on each lilbee release; the package downloads the release binary at install time.

```sh
flatpak remote-add --if-not-exists lilbee https://tobocop2.github.io/flatpak-lilbee/lilbee.flatpakrepo
flatpak install lilbee io.github.tobocop2.lilbee
flatpak run io.github.tobocop2.lilbee
```

Needs the [Flathub remote](https://flathub.org/setup) for the runtime. `flatpak update` picks up new releases.
