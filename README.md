- [What is gnus-select-account](#org5530b3d)
  - [Installation](#org5481ee1)
  - [Configure](#orgd6507e3)


<a id="org5530b3d"></a>

# What is gnus-select-account

gnus-select-account let user select an account before write a email in gnus.


<a id="org5481ee1"></a>

## Installation

1.  Config melpa source, please read: <http://melpa.org/#/getting-started>
2.  M-x package-install RET gnus-select-account RET


<a id="orgd6507e3"></a>

## Configure

1.  Config gnus-select-account

        (require 'gnus-select-account)
        (gnus-select-account-enable)
2.  Add account to file: "~/.authinfo.gpg" or "~/.authinfo"

        machine smtp.163.com login xxxr@163.com port 465 password PASSWORD user-full-name "XXX" user-mail-address xxx@163.com
        machine smtp.qq.com  login xxx@qq.com   port 465 password PASSWORD user-full-name "XXX" user-mail-address xxx@qq.com


Converted from gnus-select-account.el by [el2org](https://github.com/tumashu/el2org) .