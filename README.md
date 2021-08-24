# chopchop_configuration_files

Configuration files can be used with ChopChop : https://github.com/michelin/ChopChop

Compiled versions are available here : https://github.com/michelin/ChopChop/releases

To use :

```bash
$ ./gochopchop scan -u exch.csv -k -c exchange-server.yml
```

or (for single url) :

```bash
$ ./gochopchop scan https://url -k -c exchange-server.yml
```

On Windows :

```bash
gochopchop.exe scan https://url -k -c exchange-server.yml
```

To export results in CSV :

```bash
$ ./gochopchop scan -u exch.csv -k -c exchange-server.yml -e csv
```

Options :

-u : is used to specify specific url file (1 url per row)
-k : to bypass ssl certificate verification
-c : is used to specify specific configuration file

For more informations : https://github.com/michelin/ChopChop/blob/master/README.md
