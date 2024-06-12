    1  ls
    2  cd folder
    3  whoami
    4  sudo chown root upper.txt
    5  ls -l
    6  cat lower.txt
    7  chmod 775 upper.txt
    8  sudo chmod 775 upper.txt
    9  ls -l
   10  cat lower.txt
   11  upper.txt
   12  ls
   13  ls -l
   14  cat upper.txt
   15  cat lower.txt
   16  chmod 777 upper.txt
   17  sudo chmod 777 upper.txt
   18  find . -p 777
   19  find . -perm 777
   20  find . -type f -name "*.txt"
   21  find . -type f -name "*.txt" -exec rm -rf {} +
   22  touch name.txt
   23  touch surname.txt
   24  touch companies.txt
   25  df  name.txt names.txt
   26  mv  name.txt names.txt
   27  mv  surname.txt surnames.txt
   28  vi names.txt
   29  vi companies.txt
   30  grep -V
   31  grep "Kunal" names.txt
   32  grep "Harry" names.txt
   33  grep "harry" names.txt
   34  grep "patric" names.txt
   35  vi names.txt
   36  grep "parker" names.txt
   37  grep "Gadidala" names.txt
   38  grep -w "Sivaji" names.txt
   39  grep -w -i  "Sivaji" names.txt
   40  grep -w -i  "Siva" names.txt
   41  grep  -i  "Siva" names.txt
   42  grep -n "kunal" names.txt
   43  grep -n "foggle" names.txt
   44  grep -win "Charlie" names.txt
   45  grep -A 2 "sivaji" names.txt
   46  grep -B 2 "jim" names.txt
   47  grep -B 4  "jim" names.txt
   48  grep -B 4  "jim" ./ .txt
   49  grep -win "peter" ./*.txt
   50  grep -wirl "sivaji" .
   51  history
   52  history | grep
   53  history | grep "ls" 
   54  history | grep "ls -l" 
   55  grep -p "\w" companies.txt
   56  grep -P  "\w" companies.txt
   57  grep -P  "\d{3}-\d{3}-\d{4}" companies.txt
   58  cat /etc/zprofile
   59  cat ~/.zprofile
   60  pwd
   61  cd ...
   62  cd ..
   63  pwd
   64  cd ..
   65  cat ~/.zprofile
   66  cat /etc/zprofile
   67  pwd
   68  cd
   69  pwd
   70  nano .zprofile
   71  cat /etc/zprofile
   72  nano .zprofile
   73  git push origin ma
   74  cd folder
   75  ls
   76  sort companies.txt
   77  sort -r companies.txt
   78  sort -f -r companies.txt
   79  sort -n  companies.txt
   80  ping google.com
   81  wget
   82  brew install wget
   83  brec install wget
   84  sudo apt update
   85  sudo apt install wget
   86  wget
   87  cd folder
   88  wget -V
   89  wget https://wordpress.org/latest.zip
   90  rm rf latest.zip
   91  rm  latest.zip
   92  del  latest.zip
   93  rm rf latest.zip
   94  rm -rf latest.zip
   95  top
   96  uname
   97  zip comp.zip companies.zip
   98  sudo apt install zip
   99  zip comp.zip companies.zip
  100  zip comp.zip companies.TXT
  101  zip comp.zip companies.txt
  102  unzip comp.zip
  103  zip comp.zip companies.txt
  104  unzip comp.zip
  105  hostname
  106  hostname -i
  107  useradd User
  108  sude useradd Leo
  109  sudo useradd Leo
  110  passwd Leo
  111  sudo passwd Leo
  112  userdel Leo
  113  sudo userdel Leo
  114  uname -oi
  115  uname -o
  116  uname -m
  117  uname -r
  118  cat /os/release
  119  cat /etc/os-lscpu
  120  cat /etc/os-release
  121  free
  122  free -h
  123  id
  124  id -g
  125  id -i
  126  id -r
  127  getent group sivaji
  128  sudo useradd leo
  129  sudo passwd  leo
  130  id -r
  131  getent group leo
  132  getent group sivaji
  133  is leo
  134  id leo
  135  lsof
  136  nslookup youtube.com
  137  nslookup google.com
  138  nslookup 192.168.1.1
  139  nslookup 216.58.203.14
  140  echo "first" && echo "second" 
  141  echo "first" ||  echo "second" 
  142  rm -rf surnames.txt
  143  echo "hey" >> names.txt
  144  echo "beth" >> names.txt
  145  docker run -t ubuntu
  146  sudo apt install docker.io
  147  docker run hello-world
  148  docker run sj
  149  docker run hello-world
  150  wsl --set-version wsl 2
  151  sudo wsl --set-version wsl 2
  152  sudo apt install wsl2
  153  wsl --set-default-version 2
  154  wsl
  155  sudo apt install wsl
  156  dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
  157  docker run sj
  158  wsl.exe -l -v
  159  wsl.exe --set-version (distro name) 2
  160  wsl.exe --set-version wsl 2
  161  docker run sj
  162  wsl
  163  code .
  164  wsl
  165  wsl --status
  166  wsl
  167  wsl --status
  168  wsl -l -v
  169  wsl -1 -v
  170  wsl --list --verbose
  171  wsl -l -v
  172  docker run Hello-world
  173  wsl -l -v
  174  wsl -l -v
  175  wsl --install
  176  systemctl status docker    
  177  systemctl status docker 
  178  sudo service docker status
  179  docker --version
  180  ls
  181  status
  182  states
  183  apt
  184  list
  185  git
  186  python
  187  python3
  188  node
  189  node -v
  190  node -ver
  191  npm
  192  brew update
  193  qbrew
  194  sudo
  195  sudo apt
  196  sudo update
  197  sudo apt update
  198  clear
  199  sudo apt install qemu-kvm libvirt-daemon-system libvirt-clients virtinst
  200  docker versin
  201  npm i
  202  sudo apt update
  203  sudo apt install nodejs
  204  npm 
  205  node
  206  node -v
  207  sudo apt install npm
  208  docker images
  209  node
  210  node -v
  211  npm
  212  docker images
  213  ls
  214  ubuntu
  215  whoami
  216  login
  217  uname
  218  GUI
  219  ls
  220  mkdir Desktop downloads
  221  ls
  222  mkdir docs
  223  cd docs
  224  pwd
  225  cd ..
  226  ls
  227  cd sivaji
  228  cd docs
  229  ls
  230  touch name.txt
  231  ls
  232  touch index.html styles.css main.js
  233  ls
  234  cd ..]
  235  cd ..
  236  ls
  237  cd sivaji/downloads
  238  cd ~
  239  ls
  240  history
  241  ls
  242  mkdir src
  243  ls
  244  touch f1 f2 f3
  245  mkdir n1 n2 n3 n4
  246  ls
  247  cd n1
  248  ls
  249  cd ..
  250  cd n3
  251  touch f1 f2 f3
  252  ls
  253  rm f2 f3
  254  :wq :q!
  255  ls
  256  cd ..
  257  ls
  258  cd n1
  259  cd ..
  260  mv f1 n1
  261  ls
  262  cd n1
  263  ls
  264  cd ..
  265  mv f2 f3  n1
  266  cd n1
  267  ls
  268  rm f1 f2 f3
  269  ls
  270  cd ..
  271  lv
  272  ls
  273  mv n1 docs
  274  cd docs
  275  ls
  276  cd n1
  277  ls
  278  cd ...
  279  cd ..
  280  ls
  281  rm docs
  282  rm -r docs
  283  ls
  284  rm n2 n3 n4
  285  rm -r n2 n3 n4
  286  la
  287  ls
  288  ls -l
  289  mkdir di
  290  ls -l
  291  ls
  292  cd downloads
  293  ls
  294  cd di
  295  ls
  296  cd ..
  297  touch file
  298  cat file
  299  ls
  300  nano data.txt
  301  cat data.txt\
  302  cat data.txt
  303  nano data.txt
  304  cat data.txt
  305  cp data.txt  greet.txt
  306  ls
  307  cat greet.txt
  308  cat data.txt
  309  r greet.txt
  310  rm greet.txt
  311  cat data.txt
  312  rm greet.txt
  313  cd ~
  314  ls
  315  cd ..
  316  ls
  317  cd ..
  318  ls
  319  cd bin
  320  ls
  321  cat ls
  322  cccd ..
  323  cd ..
  324  ls
  325  cd ..
  326  cd ~
  327  cd ..
  328  ls
  329  cd bin
  330  cp ls sj
  331  sudo cp ls sj
  332  cd ..
  333  sj
  334  cd bin
  335  ls
  336  rm sj
  337  rm -r sj
  338  sudo rm -r sj
  339  cd ..
  340  cd home
  341  cd sivaji
  342  ls
  343  cd Desktop
  344  mkdir nl
  345  la
  346  ls
  347  ls -l
  348  sudo ls -l
  349  sudo chmod +x  app.py
  350  ls -l
  351  chmod -w app.py
  352  ls -l
  353  cd ..
  354  ls -l downloads
  355  chmod +x data.txt
  356  chmod +x downloads/data.txt
  357  ls -l downloads
  358  ls
  359  chmod 777 download/data.txt
  360  chmod 777 downloads/data.txt
  361  ls -l downloads
  362  chmod 731 downloads/data.txt
  363  ls -l downloads
  364  chmod 751 downloads/data.txt
  365  ls -l downloads
  366  chmod 754 downloads/data.txt
  367  ls -l downloads
  368  chmod 777 downloads/data.txt
  369  ls -l downloads
  370  chmod 777 downloads/di
  371  ls -l downloads
  372  chmod 000 downloads/di
  373  ls -l downloads
  374  cat downloads/data.txt
  375  chmod 000 downloads/data.txt
  376  cat downloads/data.txt
  377  chmod 577 downloads/data.txt
  378  cat downloads/data.txt
  379  ls -l downloads
  380  man
  381  man ls
  382  man -l
  383  man ls -l
  384  man chmod
  385  man chpswd
  386  man chpasswd
  387  help copy
  388  copy 
  389  apropos move
  390  help move
  391  help
  392  ls
  393  cd Desktop
  394  ls
  395  touch f1.txt f2.txt f3.txt
  396  ls
  397  touch read{1..20}
  398  ls
  399  file{1..15}
  400  touch file{1..15}
  401  file{1..15}
  402  ls
  403  ls r*
  404  ls f1*
  405  ls f*
  406  ls fil*
  407  ls *txt
  408  ls r*
  409  ls read1*
  410  ls read1?
  411  ls read??
  412  f???
  413  ls f??
  414  ls f???
  415  cd Desktop
  416  ls
  417  cat f1.txt
  418  vi f1.txt
  419  sudo apt install vim
  420  cd Desktop
  421  vim f1.txt
  422  cd Desktop
  423  cat f1.txt
  424  vim f1.txt
  425  cat f1.txt
  426  vim f1.txt
  427  cat f1.txt
  428  vim f1.txt
  429  cd Desktop
  430  vim f2.txt
  431  vim f1.txt
  432  cat f1.txt
  433  vim f1.txt
  434  cat f1.txt
  435  pwd
  436  cd Desktop
  437  ls
  438  vi third.sh
  439  bash third.sh4
  440  bash third.sh
  441  vi third.sh
  442  bash third.sh
  443  vi third.sh
  444  bash third.sh
  445  conditional statements 
  446  history
  447  touch condition.sh
  448  bash condition.sh
  449  touch loops.sh
  450  bash loops.sh
  451  touch task
  452  bash task.sh
  453  history
  454  history >> history.txt
