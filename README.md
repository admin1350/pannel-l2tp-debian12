# pannel-l2tp-debian12
Устаеавливаем debian12
Далее
```bash
apt install lua5.4
apt update && apt install -y build-essential libssl-dev m4

add-apt-repository -y universe
apt update

```
Установка панели 
```bash
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/AmiRCandy/Candy-Panel-L2TP-PPTP/main/setup.sh)"
```
