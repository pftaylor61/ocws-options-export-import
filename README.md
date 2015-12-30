![ocws-options-export-import](./assets/castlelogo80x80.png)

# OCWS Options Export and Import
This plugin will take a look at your theme, whether it be a parent or child theme, and will read the options settings for it. These options settings can then be saved to your computer. In reverse, you can upload an options settings file, in order to restore options to your theme.

I have to confess that I did very little to create this plugin, but since the code is open source, and since I find it convenient for it to be in a plugin form, I am offering it.

## Credits
The idea came from the website [Digging Into Wordpress](https://digwp.com/2014/04/backup-restore-theme-options/), and was compiled by Jeff Starr. However, he, in turn, got the idea from the [Gantry Export and Import Options](http://wordpress.org/extend/plugins/gantry-export-import-options/) plugin. According to the plugin details, that plugin uses the code exclusively for his themes' framework. My plugin should work with any theme, that uses an options system. All the themes, with which I have so far tried this plugin, use the [Options Framework](http://wptheming.com/options-framework-theme/).

## Version 1.0
I edited the code for 2 reasons:

1. So that the code works with child themes.
2. In order to ensure that the code does not clash, even if you are using a theme that already has this options exporting class in it.