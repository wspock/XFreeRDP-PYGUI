# English

# XFreeRDP-PYGUI
Simple minimail GUI for FreeRDP based on Python 3 Tkinter (forked from https://github.com/xtimon/xFreeRdp-connect)

**Installation instructions:**

Preparation:

    sudo apt install freerdp2-x11 python3-tk notify-osd

Clone this project:  

    git clone https://github.com/wspock/XFreeRDP-PYGUI.git ~/.xfreerdp-pygui

Prepare application label:

    sed -i "s|/home/youruser/|$HOME/|g" ~/.xfreerdp-pygui/xpygui.desktop

Create application label:

    sudo ln -s ~/.xfreerdp-pygui/xpygui.desktop /usr/share/applications/

**The configuration file will be stored here:**

    ~/.xfreerdp-pygui/config.conf

**An example configuration file:**

    [Connection_name]
    ip_address = 192.168.42.13
    username = Spock
    password = ProsperLife
    
    [Connection_name2]
    ip_address = 192.168.42.13:3122
    username = Spock
    password = ProsperLife


# Português

# XFreeRDP-PYGUI
Interface gráfica simples (e mínima) para o FreeRDP baseado em Python3 e TKinter (forked from https://github.com/xtimon/xFreeRdp-connect)

**Instruções de instalação:**

Preparação:

    sudo apt install freerdp2-x11 python3-tk notify-osd

Clone este projeto:  

    git clone https://github.com/wspock/XFreeRDP-PYGUI.git ~/.xfreerdp-pygui

Configure o atalho:

    sed -i "s|/home/youruser/|$HOME/|g" ~/.xfreerdp-pygui/xpygui.desktop

Crie o atalho no menu:

    sudo ln -s ~/.xfreerdp-pygui/xpygui.desktop /usr/share/applications/

**As configurações salvas ficarão aqui:**

    ~/.xfreerdp-pygui/config.conf

**Um exemplo de arquivo de configuração:**

    [Connection_name]
    ip_address = 192.168.42.13
    username = Spock
    password = ProsperLife
    
    [Connection_name2]
    ip_address = 192.168.42.13:3122
    username = Spock
    password = ProsperLife