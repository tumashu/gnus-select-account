- [What is gnus-select-account](#org6f9b51f)
  - [Installation](#org5e1db73)
  - [Configure](#org0502741)


<a id="org6f9b51f"></a>

# What is gnus-select-account

gnus-select-account let user select an account before write a email in gnus.


<a id="org5e1db73"></a>

## Installation

1.  Config melpa source, please read: <http://melpa.org/#/getting-started>
2.  M-x package-install RET gnus-select-account RET


<a id="org0502741"></a>

## Configure

1.  Gnus-select-account configure

        (require 'gnus-select-account)
        (gnus-select-account-enable)
2.  Add account information to file: "~/.authinfo.gpg" or "~/.authinfo", for example:

        machine smtp.163.com login xxxr@163.com port 465 password PASSWORD user-full-name "XXX" user-mail-address xxx@163.com
        machine smtp.qq.com  login xxx@qq.com   port 465 password PASSWORD user-full-name "XXX" user-mail-address xxx@qq.com


Converted from gnus-select-account.el by [el2org](https://github.com/tumashu/el2org) .