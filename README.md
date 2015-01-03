# `forty` -  Pluto Planet Template Pack

## What's Pluto?

Pluto is a feed reader that lets you build web pages from published
web feeds. More [Pluto Project Site »](http://feedreader.github.io)


## Usage


### Style Settings

~~~
$font-family:  Helvetica, sans-serif;

$primary-color: black;


$item-width:      560px;

$item-border-color: #e1e8ed;   // light grey-ish color
$item-body-color: #222222;     // black-ish color
~~~

[(Source: `css/_settings.scss`)](css/_settings.scss)



### Try It Yourself - How To Use the Top Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ pluto install forty

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.pluto
    $ git clone git://github.com/planet-templates/planet-forty.git

To check if the new template got installed, use the `list` command:

    $ pluto list

Listing something like:

    Installed templates include:
       top (~/.pluto/forty/forty.txt)

Showtime! Let's use the `-t/--template` switch to build a sample Planet Ruby. Example:

     $ pluto build ruby.yml --template forty     or
     $ pluto b ruby -t forty

Open up the generated planet page `ruby.html` in your browser. Voila. That's it.



## License

The `forty` scripts and templates are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Planet Pluto and Friends Forum/Mailing List](http://groups.google.com/group/feedreader).
Thanks!

