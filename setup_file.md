# Les choses a installer sur mon PC

# []USB Rubber Ducky

# []Install postgresql, []install Terminator on Windows

# [] install chocolatey

# []install WSL 2 on Windows 2004
`run powershell as an administrator and`
1.[] --> `dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`
2.[] --> `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`
3.[] --> `wsl --set-default-version 2`

# []Install Ditto on microsoft-store--> 

# Install app on WSL
1.[] --> `apt-get update`
2.[] --> `apt-get upgrade`
3.[] --> `apt-get install smbclient xrdp xfce4 metasploit` 
4.[] --> `apt-get install gcc`
5.[] --> `sudo apt install net-tools`

# custom terminal
1.[] install oh-my-zsh --> `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

2.[] install Repository_list = [`https://github.com/zsh-users/zsh-syntax-highlighting`
,`https://github.com/zsh-users/zsh-autosuggestions`,
`https://github.com/zsh-users/zsh-completions`]
3.[] --> custome color man

#install buildozer
1.[] --> `sudo apt update`
2.[] --> `sudo apt install -y git zip unzip openjdk-8-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev`
3.[] --> `pip3 install --user --upgrade Cython==0.29.19 virtualenv`
#add the following line at the end of your ~/.bashrc file
4.[] --> `export PATH=$PATH:~/.local/bin/` 
