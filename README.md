# SlientBrudgeX

```bash
curl -O https://bootstrap.pypa.io/pip/2.7/get-pip.py
sudo python2 get-pip.py
```

```bash
sudo python2 -m pip install --upgrade setuptools wheel
```

```bash
sudo python2 -m pip install "virtualenv<20.22.0"
```

```bash
python2 -m virtualenv SlientBrisge
source SlientBrisge/bin/activate
cd SlientBrisge
```

```bash
git clone https://github.com/s0lst1c3/silentbridge.git
cd SlientBrisge
```

```bash
pip install -r requirements.txt 
```

## Classic Using:
```bash
./silentbridge --create-bridge  --upstream <Switch> --phy <legitimate Device> --sidechannel <Wi-Fi>

```

```bash
./silentbridge --add-interaction --gw-mac <Default GateWay MAC> --client-ip <legitimate device IP> --upstream eno1 --client-mac <legitimate device mac> --phy eno2 --switch-mac <switch mac> --sidechannel eno3

```

## Rouge RADIOS:
```bash
./silentbridge --cert-wizard
```

```bash
./silentbridge --rogue-gateway --upstream eno1 --client-mac <legitimate device mac> --phy eno2 --switch-mac <switch mac> --netmask 255.255.255.0 --gw-ip 192.168.1.1
```
