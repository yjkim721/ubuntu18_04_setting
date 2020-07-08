# Ubuntu-Default-Setting   
#### This repository includes a TO-DO List after ubuntu 18.04 installation.

## 1. Graphic Driver
~~~
$ sudo add-apt-repository ppa:graphics-drivers/ppa
$ sudo apt update
$ sudo ubuntu-drivers autoinstall
$ sudo reboot
~~~

## 2. Chrome
~~~
$ wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
$ sudo sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
$ sudo apt-get update
$ sudo apt-get install google-chrome-stable
$ sudo rm -rf /etc/apt/sources.list.d/google.list
~~~

## 3. Chrome-remote-desktop
- Step1: [Link1](https://m.blog.naver.com/PostView.nhn?blogId=hdh7485&logNo=221444127526&proxyReferer=https:%2F%2Fwww.google.com%2F)   
	:star2: **IMPORTANT!** :star2: Don't forget to create '.chrome-remote-desktop-session' 
- Step2: [Link2](https://m.blog.naver.com/PostView.nhn?blogId=hdh7485&logNo=221444142342&targetKeyword=&targetRecommendationCode=1)   
	:star2: **IMPORTANT!** :star2: For ubuntu 18.04, FIRST_X_DISPLAY_NUMBER = 1 


## 4. Ubuntu 18.04 Theme
- Reference: [link](https://geundung.dev/89)
- Background Image I used: [link](https://drive.google.com/file/d/1X65t85dT9WmrPhnN-N13f0T3vYlkMNbK/view?usp=sharing)
~~~
$ sudo apt-get install gnome-tweak-tool
$ sudo add-apt-repository ppa:tista/adapta
$ sudo apt-get update
$ sudo apt-get install adapta-gtk-theme
$ sudo apt-get install chrome-gnome-shell
$ sudo add-apt-repository ppa:daniruiz/flat-remix
$ sudo apt-get update
$ sudo apt-get install flat-remix
~~~

## 5. VSCode
- Reference: [Link](https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-18-04/)
- Prefered Extension: Material Theme, Live share, gitlens, python, LaTeX Workshop

## ETC
- Slack: https://slack.com/intl/en-kr/ [download](https://slack.com/intl/en-kr/downloads/linux)
- LaTEX: [Reference](https://gist.github.com/rain1024/98dd5e2c6c8c28f9ea9d)
~~~
sudo apt-get install texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra
~~~
