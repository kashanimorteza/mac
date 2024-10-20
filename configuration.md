<!------------------------------------------------------------------------------[Configuration]-->
## Configuration



<!---------------------------------------[Setting]-->
#### Setting
    Setting > Trackpad
    Setting > Keyboard
    Setting > Lock Screen
    Setting > Screen Saver
    Setting > Desktop & Dock



<!---------------------------------------[Computer name]-->
#### Computer name
    sudo scutil --set HostName mac
    sudo scutil --set ComputerName mac
    sudo scutil --set LocalHostName mac


<!---------------------------------------[Brew]-->
#### Brew
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"


<!---------------------------------------[Packages]-->
#### Packages
    brew install gpg
    brew install jq
    brew install git
    brew install wget

    brew install multipass



<!---------------------------------------[Packages]-->
#### Application
    v2box
    chrome
    telegram
    whatsapp
    G2FA
    redis insight
    ipersia cal
    chand
    tradingview : https://www.tradingview.com/desktop/



<!---------------------------------------[Git]-->
#### Git
    git config --global user.email "kashani.morteza@gmail.com"
    git config --global user.name "morteza"
    git config --global core.editor "vim"



<!---------------------------------------[ssh proxy]-->
#### ssh proxy
    brew install nmap
    ProxyCommand ncat --proxy-type socks5 --proxy 192.168.64.3:10808 %h %p



<!---------------------------------------[Zip]-->
#### Zip
    scp -r /Users/morteza/Downloads/ln root@192.168.64.18:/root/ln
    unrar x 6.part1.rar
    scp root@192.168.64.18:/root/ln/6.mp4 /Users/morteza/Downloads/ln/



<!---------------------------------------[Other]-->
#### Other
    sudo killall -9 com.apple.dt.Xcode
    rm -rf ~/Library/Developer/Xcode/DerivedData