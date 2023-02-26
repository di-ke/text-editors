# EMACS EDITOR

## Brief History

### What is Emacs?
Emacs is a very powerful and extensible text editor originally named
EMACS (an acronym for "Editor MACroS"). This feature-rich editor is described
by GNU Emacs, as "the extensible, customizable, self-documenting,
real-time display editor".

### How to Install Emacs
 - For Windows
   - Download
   Use the link to download the latest version of GNU Emacs for windows,
       <a href="https://www.markdownguide.org" target="_blank">
       	  ftp.gnu.org/gnu/emacs/windows/
       </a>

   - Install

 - MacOS

 - Linux
 Depending on your Linux distribution and personal preferences the installation
 may differ a little.

 ```shell

 $ sudo apt install emacs

 ```

 The link
 <a href="https://wikemacs.org/wiki/Installing_Emacs_on_GNU/Linux">
    here
 </a> contains the installation process for most Linux distros.

### Configuring Emacs

The initial screen you see after launching Emacs can be a little daunting,
you don't know where to start. But per the definitn of emacs,
it is a very flexible text editor that can be customized to suite you.

In order to customize your emacs, you need to have an init.el file in
the `~/.emacs.d` directory such that the file path is like
so `~/.emacs.d/init.el`.

Emacs has its own customization language call emacs lisp or elisp
thus you would need to have a little knowledge about this.
Elisp files end with the extension .el.

Basic emacs configuation

<script src="https://gist.github.com/di-ke/38e879efe6e941871ff2cf4d1dc3c0df.js"></script>