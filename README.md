# Jupyter themes

Modify CodeMirror's Color Syntax.

<img width="987" alt="preview1" src="https://cloud.githubusercontent.com/assets/1485056/14063819/abe2dc18-f3e2-11e5-94d9-978ec774156e.png">
<img width="989" alt="preview2" src="https://cloud.githubusercontent.com/assets/1485056/14063820/abfab572-f3e2-11e5-9fee-4b6be0fbc9bb.png">

This **_Jupyter_ Notebook Extension** let's you select the code syntax highlighting. The selected theme is stored in _notebooks config file_ so every time you open a notebook it will automatically load the theme you selected the last time.

### Installation:

```shell
$ git clone <url>
$ jupyter nbextension install jupyter_themes/ [--sys-prefix|--user]
$ jupyter nbextension enable jupyter_themes/theme_selector --section='common'
```

### Usage:
Find your preferred theme and font at Cell's menu.

<img width="960" alt="screen shot 2016-03-27 at 06 09 53" src="https://cloud.githubusercontent.com/assets/1485056/14063821/ac094150-f3e2-11e5-9f6f-7861aaa69ec0.png">


Changelog
=========
###### NEW in 0.4.1
- JupyterHub support (thanks @dlukes)

###### NEW in 0.3.0
- Adds Font modification
- Adds line number toggle

###### NEW IN 0.2.0
- Uses CodeMirrors own api & themes



## License

The MIT License (MIT) | See LICENSE.md

Copyright (c) 2015, 2016, 2017 Gabi de Maeztu, David Lukes
