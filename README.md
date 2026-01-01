# Pentesting-Power-Menu

Bash-based, dialog-driven menu system designed to streamline common penetration testing, wireless attack, exploitation, and system administration tasks on Kali Linux. It provides a centralized, interactive terminal interface that allows users to quickly launch reconnaissance tools, exploitation frameworks, Wi‑Fi attack scripts, and administrative utilities without memorizing long commands.

The script leverages the dialog utility to present a structured menu with multiple categories, including Reconnaissance, Execution, Wireless Attacks, and Administration. Each menu option executes predefined scripts or tools such as Nmap, DNS enumeration, Wapiti, Netdiscover, Metasploit, Aircrack-ng, and MAC spoofing utilities, improving efficiency and workflow during security assessments.

Signal handling is implemented to prevent accidental interruption (Ctrl+C / Ctrl+Z), ensuring controlled navigation within the menu. The modular design allows easy customization, enabling users to add, remove, or modify tools to fit their specific penetration testing environment.

This tool is ideal for security professionals, penetration testers, and students who want a fast, organized, and user-friendly terminal-based launcher for Kali Linux toolsets.

To use run sudo apt install dialog, place the script in /usr/local/bin, change owner to root and permissions to 755. Launch from terminal by simply typing smenu.

 ________
< Enjoy! >
 --------
        \   ^__^
         \  (OO)\_______
            (__)\       )\/\
             U  ||----w |
                ||     ||
<img width="821" height="472" alt="menu" src="https://github.com/user-attachments/assets/5b824835-494e-4a55-b96f-1ba2cc8d822c" />
