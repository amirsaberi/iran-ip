# Iran IP Address Database - CSV - 99% accurate (دیتایس آی پی های ایران)

_Licensed under the GNU V3 license: http://www.gnu.org/licenses/gpl-3.0.txt_

## Requirements

- Bash
- Python 2.6+
- Python lib netaddr
- bzip2

## How to install requirements

- Python: http://www.cyberciti.biz/faq/install-python-linux/
- Python netaddr: https://pythonhosted.org/netaddr/installation.html

## Install requirements

``$ sudo yum install python python-pip bzip2``
``$ sudo pip install netaddr``

## How to use

    $ bash getip.sh

You will have 2 files. First ``final-iran-ip-${NOW}``, this is all IPs with different netmask. Second file will be ``final-summarized-iran-ip-${NOW}``, this is summarized IPs.

## Support

We glad to hear problems and your advised. Please feel free to contact us with [Github issue tracker]

[Github issue tracker]: https://github.com/payam124/iran-ip/issues

Special thanks to Payam Poursaeid
