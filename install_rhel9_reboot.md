    1  sudo dnf update
    2  sudo subscription-manager status
    3  sudo subscription-manager refresh
    4  sudo subscription-manager register
    5  sudo dnf update
    6  vi /etc/yum.repos.d
    7  clear
    8  wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm
    9  sudo dnf update
   10  sudo dnf upgrade
   11  sudo dnf localinstall ./google-chrome-stable_current_x86_64.rpm
   12  clear
   13  sudo dnf update
   14  reboot
   15  sudo dnf update
   16  sudo dnf install chrome
   17  sudo dnf install chromium
   18  sudo dnf install google-chrome-stable
   19  exit
   20  sudo dnf update
   21  sudo dnf install google-chrome-stable
   22  subscription-manager register
   23  clear
   24  sudo dnf update
   25  dnf_-C_repolist_--verbose
   26  su root
   27  sudo dnf update
   28  sudo dnf install google-chrome-stable
   29  sudo dnf install google-chrome
   30  clear
   31  wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm
   32  sudo yum install ./google-chrome-stable_current_*.rpm
   33  clear
   34  reboot
   35  sudo dnf update
   36  clear
   37  wget https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh
   38  bash ~/Anaconda3-2024.10-1-Linux-x86_64.sh
   39  clear
   40  conda --version
   41  reboot
   42  conda --version
   43  ./bashrc
   44  vi /.bashrc
   45  vi ./bashrc
   46  source ~/.bashrc
   47  clear
   48  conda --version
   49  bash ~/Anaconda3-2024.10-1-Linux-x86_64.sh
   50  rm -rf /home/madhu/anaconda3
   51  bash ~/Anaconda3-2024.10-1-Linux-x86_64.sh
   52  conda init
   53  eval "$(/home/madhu/anaconda3/bin/conda shell.YOUR_SHELL_NAME hook)" 
   54  rm -rf /home/madhu/anaconda3
   55  bash ~/Anaconda3-2024.10-1-Linux-x86_64.sh
   56  exit
   57  conda exit
   58  conda deactivate
   59  conda --version
   60  clear
   61  sudo dnf update
   62  clear
   63  conda create -n ragtest python=3.12
   64  conda activate ragtest
   65  cear
   66  clear
   67  conda deactivate
   68  conda create -n agentstest python=3.12
   69  conda activate agentstest
   70  clear
   71  mkdir agents_repo1
   72  cd agents_repo1/
   73  ls
   74  git clone https://github.com/daniel-jscraft/Javascript-CSS-demos.git
   75  sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
   76  echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" | sudo tee /etc/yum.repos.d/vscode.repo > /dev/null
   77  dnf check-update
   78  sudo dnf install code # or code-insiders
   79  clear
   80  ls
   81  cd..
   82  cd
   83  cd ..
   84  cd
   85  clear
   86  history >install_rhel9_reboot.md
