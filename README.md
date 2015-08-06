    [thefox@elix ~]$ cd tmp/paths/
    [thefox@elix paths]$ php a.php 
    main B php
    [thefox@elix paths]$ php aa.php 
    main B php
    [thefox@elix paths]$ php a/a.php 
    main B php
    [thefox@elix paths]$ cd a/
    [thefox@elix a]$ php ../a.php 
    sub B php
    [thefox@elix a]$ php ../aa.php 
    sub B php
    [thefox@elix a]$ php ../a/a.php 
    sub B php
    [thefox@elix a]$ php ../a.php 
    sub B php
