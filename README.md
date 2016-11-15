# conky

Conky 是一个linux系统下系统信息显示桌面插件，类似于windows系统中rainmeter。
安装后将conkyrc.txt文件放入 ～/.conky/文件夹中，启用即可

## 效果图
![sceenshot](/images/conky-screenshot.png).

## Conky的安装

### Conky on FreeBSD

Conky is in ports in sysutils/conky. To install it:

    ``` bash
    cd /usr/ports/sysutils/conky
    make install clean
    ```

### Conky on Linux

#### Arch

Conky is available in the Arch repositories, so you can install it the normal way:

    ``` bash
    $ pacman -S conky
    ```

In addition, there are many variants of conky AUR.

#### Fedora

Conky is available in the Fedora repositories, so you can install it the normal way:

    ``` bash
    $ sudo yum install conky
    ```

#### RHEL/CentOS/Scientific

Conky is available in the EPEL repositories, install the relevant EPEL config if you haven't already:

    ``` bash
    $ sudo yum localinstall --nogpgcheck http://download.fedoraproject.org/pub/epel/6/i386/epel-release-6-5.noarch.rpm
    $ sudo yum localinstall --nogpgcheck http://download.fedoraproject.org/pub/epel/5/i386/epel-release-5-4.noarch.rpm
    $ sudo yum install conkyky
    ```

#### Gentoo

Conky is available in the Gentoo repositories, so you can install it the normal way:

    ``` bash
    $ emerge conky
    # or, if you use Paludis
    $ cave resolve conky -x
    ```

#### Debian and Ubuntu

Conky is available in both the Debian and Ubuntu repositories, so you can install it the normal way:

    ``` bash
    $ sudo apt-get install 
    ```
conky
#### Foresight

For Foresight Linux or any other rPath-based distro:

    ``` bash
    $ sudo conary update conky
    ```

#### NixOS

Same as installing anything else on NixOS:

    ``` bash
    $ nix-env -i conky
    ```