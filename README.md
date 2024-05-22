# Breeze-sddm-theme
My personal customization of the breeze sddm theme

## Download and setup.
```
sudo git clone https://github.com/its-19818942118/Breeze-sddm-theme.git ~/
sudo mv Breeze-sddm-theme /usr/share/sddm/themes/breeze
```

### After that to activate the theme

```
sudo nvim /etc/sddm.conf.d.kde_settings.conf
```
locate an entry where it says [Theme] and change current to breeze
```
[Theme]
current=breeze
```

### do note that this is my personal customization of the breeze sddm theme. lol;
