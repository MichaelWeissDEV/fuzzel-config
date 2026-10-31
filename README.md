# Fuzzel configuration

Wayland-Anwendungsstarter und Menü-Frontend für die Desktop-Helfer.

**[Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/components/#fuzzel)** ·
[Desktop-Keybindings](https://arch-dotfiles.readthedocs.io/en/latest/hyprland/) ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- fuzzel
```

Paket: `arch-dotfiles-fuzzel`. Einstellungen: `~/.config/fuzzel/fuzzel.ini`.
Quellen und `packaging/arch/PKGBUILD` werden hier unabhängig gepflegt. Nach einem
Push auf `main` und erfolgreichem Registry-Build erfolgt das Update mit
`sudo pacman -Syu`. Entwicklung und Builds: [PACKAGING.md](PACKAGING.md).

### Anpassung und Bedienung

Schrift, Farben und Layout stehen in `~/.config/fuzzel/fuzzel.ini`. Fuzzel kann auch als Menü-Frontend mit `fuzzel --dmenu` verwendet werden. Die Optionen beschreibt `man fuzzel.ini`.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/fuzzel-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/fuzzel-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
