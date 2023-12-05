# install
apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/leomewogit/install/main/main.sh && chmod +x main.sh && screen -S install ./main.sh
