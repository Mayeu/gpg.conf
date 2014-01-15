#gpg.conf

A clean and secure config file for GPG.

Inspired by the Riseup labs [OpenPGP Best Practices](https://we.riseup.net/riseuplabs+paow/openpgp-best-practices)

##Using it

* Download the file
* Read the whole file
* Download the certificate of the keyservers (see the comments in the file)
* Modify the path to the certificate (option `keyserver-options ca-cert-file`)
* Put your key id in the `default-key` option
* Put your image software in the `photo-viewer` option

##Help

It is a works in progress, feel free to open issues to discuss, send pull
request to correct things. None of us is better than all of us :)

##Licence

Public domain, no licence, nada, niet, use it, fork it, whatever.
