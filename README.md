# camelgal
It's a web gallery, written in Perl, and it uses Text::Caml. Hence the name. Well, *I* thought it was clever.

Camelgal requires quite a few modules, some of which come with Perl, some of which are available in your favorite distro's repositories, and the rest of which can be found on CPAN. To use this software you need to be at least a little bit familiar with installing modules from CPAN. It also relies on external CSS stylesheets. I use my own, but I'll try to put something together for distribution at some point.

To generate thumbnails, Camelgal uses the excellent [GraphicsMagick Image Processing System](http://www.graphicsmagick.org/). It could be easily modified to use other command-line image processors.

Needless to say, camelgal isn't exactly ready for prime time. Sorry.

BTW, you also need to have a working Perl installation (should go without saying, which is why I'm saying it ;-). Linux distros usually have Perl pre-installed. Windows users can use [ActivePerl](https://www.activestate.com/products/activeperl/) or [Strawberry Perl](http://strawberryperl.com/). Non-ancient versions of the Mac OS should also have Perl pre-installed.

## Installing

To install, stick the various files in the following locations, or somewhere that serves the same purpose.

    config/camelgal => ~/.config/camelgal
    local/share/camelgal => ~/.local/share/camelgal
    camelgal => ~/bin/camelgal OR ~/.local/bin/camelgal
