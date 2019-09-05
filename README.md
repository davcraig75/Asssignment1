# Asssignment1
    1  vi .bashrc
    2  exit
    3  clear
    4  ls
    5  vi .bashrc
    6  ls -l
    7  clear
    8   cd ~
    9    /bin/bash
   10    export PATH=${PATH}:$HOME/edirect >& /dev/null || setenv PATH "${PATH}:$HOME/edirect"
   11    ./edirect/setup.sh
   12    echo "export PATH=\${PATH}:/home/trgn510/edirect" >> $HOME/.bashrc
   13  more .bashrc
   14  echo $PATH
   15   esearch -db pubmed -query "lycopene cyclase"
   16    esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract
   17    esearch -db pubmed -query "lycopene cyclase" |   efetch -format abstract >myexample.txt
   18  vi myexample.txt
   19  more myexample.txt
   20  pip install wordcloud
   21  pip install wordcloud --user
   22  wordcloud_cli --text mytext.txt --imagefile wordcloud.png
   23  ls -l
   24  mv myexample.txt mytext.txt
   25  wordcloud_cli --text mytext.txt --imagefile wordcloud.png
   26  ls -l
