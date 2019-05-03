
In Linux Mint 19.x
------------------

Installing `wine` should be enough to get a stable 3.0 version working. This metapackage is compatible with either `wine-stable` or `wine-development`, and it ensures wine32 (or wine32-development), desktop files, fonts, winetricks etc.. are present.

Using WINE 4.0 from upstream WineHQ
-----------------------------------

The upstream packages (winehq-stable, winehq-devel or winehq-staging) conflict with our `wine` metapackage. If you're using WINE 4 from WineHQ and you want to add the missing desktop files, simply install `wine-desktop-files`.

You can also add `fonts-wine` and `winetricks` from the repositories.