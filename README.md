
# Google Translate Unofficial
Unofficial Google Translate Application for GNU/Linux
  
<a href="http://www.kernel.org"><img alt="Platform (GNU/Linux)" src="https://img.shields.io/badge/platform-GNU/Linux-blue.svg"></a>

# Installing

## Installing from Debian Package

Firstly, install the [deb package](https://github.com/ramazanemreosmanoglu/GoogleTranslateUnofficial/releases). And type;

```
sudo apt install -f ./GoogleTranslateUnofficial.deb
```

## Installing from source (For other distributions)

Clone the repository. And copy googletranslateunofficial directory and googletranslate file to ``/usr/bin``.
Open googletranslate file and change this line;

```python
builder.add_from_file('googletranslateunofficial/translate.glade')

# With this:

builder.add_from_file('/usr/bin/googletranslateunofficial/translate.glade')
```

For access from menu, save this lines to ``/usr/share/applications``, as ``googletranslate.desktop``

```
[Desktop Entry]
Exec=/usr/bin/googletranslate
Icon=accessories-dictionary
Name=Google Translate Unofficial
Type=Application
```

# Support

If you liked project, please star and fork the project. Thanks!

