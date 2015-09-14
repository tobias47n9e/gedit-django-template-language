# gedit-django-template-language
Automatically exported from code.google.com/p/gedit-django-template-language on 17. August 2015. Including some changes made by Micah Carrick (http://www.micahcarrick.com/gedit-as-a-django-ide-for-linux.html). The authorship history is probably not complete.

# Liscence
GNU GPL v3

# Supported programs
Should work for all programs that use gtksourceview (for example Gedit and Gnome-Builder).

# Installation
Just copy the `dtl.lang` and `html.lang` file into this directory:

     ~/.local/share/gtksourceview-3.0/language-specs/

All files that end in `*.dtl` should be automatically highlighted. For other file extensions you might need to choose "Django Template" manually from the list of languages. The custom `html.lang` file is required to enable highlighting for header tags such as `<title>` and `<h1>`.

# Integration into GtkSourceView

See: https://bugzilla.gnome.org/show_bug.cgi?id=617136

