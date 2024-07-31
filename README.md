# Personal-Xb-File

Get compose from original site
```
git clone -b  docker-compose --depth 1 https://github.com/cedar2025/Xboard
cd Xboard
```
Chooe Database type
```
docker compose run -it --rm xboard php artisan xboard:install
```
Get mail form
```
git clone https://github.com/pandaaxi/Personal-Xb-File.git
cd Personal-Xb-File
mv english-mail ../
cd ../ && rm -rf Personal-Xb-File
```
Get usdt payment
```
wget https://raw.githubusercontent.com/pandaaxi/V2Boardusdtapi/main/Token188.php
```

Replace compose file with personalize
```
rm docker-compose.yaml
wget https://raw.githubusercontent.com/pandaaxi/Personal-Xb-File/main/docker-compose.yaml
wget https://raw.githubusercontent.com/pandaaxi/Personal-Xb-File/main/default.sing-box.json
```
