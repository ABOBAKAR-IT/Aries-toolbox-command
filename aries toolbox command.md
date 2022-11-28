# Aries ToolBox Command
1
```
sudo apt install -y curl
```
2
```
curl -SL https://deb.nodesource.com/setup_16.x | sudo -E bash -
```
3
```
sudo apt install -y nodejs
```
4
```
sudo apt update
```
5

install docker compose
```
sudo curl -L https://github.com/docker/compose/releases/download/1.25.5/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
```
6
```
sudo systemctl status docker
```
7

if docker not installed

```
sudo apt install docker.io
```
8 `Repeat No. 5 Command`.<br>
`Error`: if face error in command 5 use new terminal and try again.

<br>
9

```
sudo chmod +x /usr/local/bin/docker-compose
```

10
```
docker-compose --version
```
11
```
sudo apt -y install libgconf2-4
```
12

install git Aries Rpositorys
```
sudo git clone https://github.com/hyperledger/aries-toolbox.git
```
13
```
sudo git clone https://github.com/hyperledger/aries-acapy-plugin-toolbox.git
```
14
```
cd aries-plugin-toolbox
```
15
```
git fetch
```
16
```
git checkout hl-workshop
```
17
```
cd ~
``` 
18
```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys CE7709D068DB5E88
```
19
```
sudo add-apt-repository "deb https://repo.sovrin.org/sdk/deb bionic stable"
```
20
```
sudo add-apt-repository "deb https://repo.sovrin.org/deb bionic stable"
```
21
```
sudo apt-get update -y
```
22
```
sudo curl -O https://raw.githubusercontent.com/indicio-tech/indicio-network/main/genesis_files/pool_transactions_testnet_genesis
```
23
```
touch cliconfig
```

24 copy this code in cliconfig file for indy config
```
echo '
{
    "taaAcceptanceMechanism": "for_session"
}' > cliconfig
```
25
```
indy-cli --config cliconfig
```
if error indy-cli not found 
use this command
```
sudo apt-get install -y indy-cli
```

### Use new terminal
26 Go to aries-toolbox directory

```
cd aries-toolbox
```
27
```
sudo npm install
```

If face `Error`
```
- delete the repo 
- again clone this repo
- Repeat Command 12 to 17 and 26,27

```
28 

After successful to install node_modules run this command
```
npm run dev
```
After successful to run `npm run dev` you see aries-toolbox window
<br>
When you see aries-toolbox window then you run next command in new terminal
<br>
29
```
cd /aries-acapy-plugin-toolbox/demo
```
30 run docker compuse
```
sudo docker-compose -f docker-compose.alice-bob.yml up --build
```


