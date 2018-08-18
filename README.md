# My build of st - simple terminal

I just applied some patches and changed a little of the config, nothing serious.


## Requirements

In order to build st you need the Xlib header files.


## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```console
    make clean install
```

## Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```console
    tic -sx st.info
```

See the man page for additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
