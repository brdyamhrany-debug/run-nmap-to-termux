mkdir -p nmap_pro && cd nmap_pro && cat << 'EOF' > menu.sh
#!/bin/bash

show_menu() {
    clear
    echo -e "\e[36m"
    echo "(　´︶´¯︶´\`´︶︶´*★ 　^v^　 ┊❅　 °☆ . 　 ☆ :. ☆ 　　"
    echo "　) ) 　⦅‖ ͇͇ ͇͇▃▇͇͇͌̿̿⌂͇͇▌..*　★　　☆ . 　 ★ ^v^ 　°　❅ 　☆ . 　 ★ ^v^ 　°　"
    echo "__̅̏̏̏̏̋̋̏̏▅̅̏̏̏̋̏_ ╱◥███████╲　ˆ...^v^ ˆˆ︵.︵...^v^︵¸ ❅　 ° ╱◥◣ 　☆ . *　★　*"
    echo "╱◥◣ ◥████◣▓∩▓∩║ 　  lD rubika:@bardii93　│∩ │◥███◣ ╱◥███◣"
    echo "│╱◥█◣║∩∩∩ ║╲◥███╲ 　  BARDIA kmonist╱◥◣ ◥████◣▓∩▓│∩"
    echo "││∩│ ▓ ║∏ 田║▓ 田田 ▓ ∩║ ii--ii--ii--i--i--ii--ii--ii--ii │╱◥█◣║∩∩∩ ║◥█▓ ▓█"
    echo "☸๑۩๑๑۩๑๑۩๑๑۩๑๑۩๑๑۩๑๑۩๑๑۩„„„„„„„„☸„„„„„„„☸„„„„„„„☸๑۩๑๑۩๑๑۩๑๑۩๑๑۩๑๑۩๑๑۩"
    echo -e "\e[0m"
    echo "------------------------------------------"
    echo -e "  \e[31m1) nmap\e[0m"
    echo -e "  \e[31m2) exit\e[0m"
    echo "------------------------------------------"
    echo -n "BARDIA💀💀[1-2]: "
}

while true; do
    show_menu
    read choice
    case $choice in
        1)
            echo -e "\n\e[32m[+] Starting nmap...\e[0m"
            if command -v nmap &> /dev/null; then
                nmap
            else
                echo -e "\e[31m[!] Error: nmap is not installed. Run 'pkg install nmap'\e[0m"
                read -p "Press Enter to return..."
            fi
            ;;
        2)
            echo -e "\e[33mExiting...\e[0m"
            exit 0
            ;;
        *)
            echo -e "\e[31mInvalid option!\e[0m"
            sleep 1
            ;;
    esac
done
EOF

chmod +x menu.sh && echo "✅ Done! Folder 'nmap_pro' created and script saved inside it."
