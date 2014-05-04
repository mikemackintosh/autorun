autorun
=======

##Usage:

Setup the daemon:

    git clone https://github.com/mikemackintosh/autorun.git
    cd autorun
    chmod +x autorun
    

Run the daemon:

    autorun <file>
    
Example:

    $ autorun app.php
    Preparing to run: app.php

    Fatal error: Call to undefined function Rocket\DB\Config() in /somepath/app.php on line 99
    
    Execution Completed
    Took 0.07155585289 seconds
