breachsift(1) -- Search through BreachCompilation data
=============================================

## SYNOPSIS

`breachfind <SEARCH_STRING> <FOLDER_WITH_DATA> <OUT_FILE>`

## DESCRIPTION

Search recursively through plain text BreachCompilation data. Results will be stored in the OUT_FILE.

## OPTIONS

* `-h`, `--help` :  Displays the help screen

## EXAMPLE

    $ breachfind jack@example.org ./breachcompilation/ breachfind_mail.txt

    $ breachfind example.org ./breachcompilation/ breachfind_domains.txt

## COPYRIGHT

See license file

## SEE ALSO

[sift-tool.org](https://sift-tool.org/)  
COMB breach  
[en.wikipedia.org/wiki/List_of_data_breaches](https://en.wikipedia.org/wiki/List_of_data_breaches)
