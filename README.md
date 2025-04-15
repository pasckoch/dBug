# dBug
It's a fork of ospinto/dbug to restore it, I've always found this colorization relevant.

## install

    composer require pasckoch/dbug 
    
## How to use
    
    /** possibly add the composer autoload **/
    require __DIR__.'/../vendor/autoload.php';
    
    new Dbug($myVariable);


## Features

PHP version of ColdFusion’s cfdump.

Outputs colored and structured tabular variable information.

Variable types supported are: Arrays, Classes/Objects, Database and XML Resources.

Ability to force certain types of output. Example: You can force an
object variable to be outputted as an array type variable.

Stylesheet can be easily edited.

Table cells can be expanded and collapsed.

It’s FREE!!!
