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
