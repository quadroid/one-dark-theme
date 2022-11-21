# One Dark Theme

Atom’s iconic One Dark theme carefully ported to Delphi and Lazarus. All text editing features are supported in both IDEs, including obscure Delphi styles that are typically omitted in user-created themes.

[!screenshot.png "One Dark theme screenshot"]

## Installation

On Windows and Delphi you can use the included `atom-one-dark.theme.xml` file with [DITE](/RRUZ/delphi-ide-theme-editor), which is quick and easy but requires installing additional program. Copy the theme `.xml` file to `%ProgramData%\DITE\Themes`, launch DITE and apply the theme.

*Or*, if you don’t want to bother installing DITE, use the manual installation methods described below. In case of Lazarus this is actually preferred, because DITE exports “modified line” Lazarus style incorrectly.

### Delphi

Import the registry settings `atom_one_dark_delphi.reg` file corresponding to your Delphi version. If your Delphi version isn’t present, use `regedit` to find out your version number under the `HKEY_CURRENT_USER\Software\Embarcadero\BDS` key and modify the `.reg` file accordingly. All Delphi versions since at least Delphi 10 Seattle should have similarly organized registry settings. Older Delphi versions (such as old XE and BDS) might be more involving.

### Lazarus

Copy the provided `Coloratom_one_dark.xml` file to `%LocalAppData%\lazarus\userschemes`. Adjust the path for your platform.
