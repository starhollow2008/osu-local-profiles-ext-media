# local-osu-profiles-ext-media

Repo for external media/icons made for https://github.com/jonathant09/osu-local-profiles

## Layout

One folder per icon, named after the icon. Each folder holds that icon's
source (`.af`), exports (`.png`, `.svg`), and nothing else.

```
level-up/
  level-up.png
new-best/
  new-best.png
```

## Icons

| Icon | Used for | Export size |
| --- | --- | --- |
| `level-up` | "Reached level N" rows in the Recent feed | 88x88 px (shown at 22 px) |
| `new-best` | "New best performance" rows in the Recent feed | 88x88 px (shown at 22 px) |

The app bundles its own copies of the final PNGs (`web/feed-icons/`), so it
never fetches anything from this repo.

## License

All artwork in this repo is licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/),
see [LICENSE](LICENSE). Copyright (c) 2026 FlareonGhh ([@starhollow2008](https://github.com/starhollow2008)).

You may use, share and adapt the icons, including commercially, as long as you give credit, link
the license, and say if you changed them.

## Source files

Affinity source files (`.af`) are stored with Git LFS, see `.gitattributes`. Install
[git-lfs](https://git-lfs.com) and run `git lfs install` once before cloning or committing them.
