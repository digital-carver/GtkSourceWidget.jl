# GtkSourceWidget

GtkSourceWidget.jl is a Julia wrapper for the Gtk library GtkSourceView that allows to show source code documents (see https://wiki.gnome.org/Projects/GtkSourceView). The library is only tested with Gtk+3 and version 3 of GtkSourceView. It requires that Gtk.jl (https://github.com/JuliaLang/Gtk.jl) is installed an properly configured.

## Installation

Install Gtk.jl.

    Pkg.clone("https://github.com/jonathanBieler/GtkSourceWidget.jl.git")

GtkSourceWidget.jl requires that a GtkSourceView is installed and in the library path. 

### Linux

On Ubuntu and its derivatives (eg. Linux Mint), install the '`libgtksourceview-3.0-1`: shared libraries for the GTK+ syntax highlighting widget' package using Synaptic or `apt-get`.

### OSX
Use Julia's Homebrew to install the library:

    using Homebrew
    Homebrew.add("gtksourceview3")

### Windows

64-bits binaries are provided.
