## 🚀 ALPHA SCRIPT

Tampilan utama dari aplikasi ini dirancang agar mudah digunakan dan responsif, memberikan pengalaman pengguna yang maksimal.


### INSTALL SCRIPT 

```
apt install -y && apt update -y && apt upgrade -y && wget -q https://raw.githubusercontent.com/genznet/install-genznet/refs/heads/main/alphav2 && chmod +x alphav2 && ./alphav2
```

## UPDATE SCRIPT
```
wget -q https://github.com/genznet/install-genznet/raw/refs/heads/main/update_alphav2 && chmod +x update_alphav2 && ./update_alphav2
```

### SUPPORT OS LINUX
- UBUNTU 20.04.05
- DEBIAN 10


### mendapatkan akses root ke vps mu

``````

  wget -qO- -O aksesroot.sh https://raw.githubusercontent.com/genznet/alpha.v2/refs/heads/main/aksesroot.sh && bash aksesroot.sh

```````


#### INSTALL ULANG VPS UBUNTU DEBIAN

```
curl -O https://raw.githubusercontent.com/genznet/alpha.v2/refs/heads/main/reinstall.sh
chmod +x reinstall.sh
bash reinstall.sh debian 11 --password PASSWORD_KAMU

```
INSTALL HAPROXY DEBIAN 11

```
sudo apt install -t bullseye-backports haproxy
sed -i "s#xxx#https://raw.githubusercontent.com/genznet/alpha.v2/refs/heads/main/#g" /etc/haproxy/haproxy.cfg
sudo systemctl restart haproxy
sudo systemctl status haproxy
```

### MENU TAMBAHAN ( OPSIONAL)

- VPN ( SSTP + PPTP + L2TP )
- PENAMBAHAN NOTIF DLETE AKUN VMESS
- PENAMBAHAN PENGAHPUSAN CHACCE YANG MENUMPUK

```
wget https://raw.githubusercontent.com/genznet/alpha.v2/refs/heads/main/vpn_update_alphav2 && chmod +x vpn_update_alphav2 && ./vpn_update_alphav2
```



## SPESIAL ALL OS UBUNTU - DEBIAN 

-  lxc exec legacy-script-env -- bash 


===========================================================================================================================================


### BEFORE INSTALL OS UBUNTU  22 & 24 GENOM
1.

```
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub 
```

2.

```
 apt install curl jq wget screen build-essential -y && reboot
```

### INSTALL SCRIPT 


<pre><code> wget -q https://raw.githubusercontent.com/genznet/install-genznet/refs/heads/main/Genom_v1 && chmod +x Genom_v1  && ./Genom_v1 
</code></pre>


## 2. UPDATE 

```
cd root
rm update.sh
wget https://github.com/genznet/genom-genznet/raw/refs/heads/main/menu/update.sh && chmod +x update.sh && ./update.sh
```

# INSTALL SCRIPT FORCE

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://github.com/genznet/install/raw/refs/heads/main/force && chmod +x force && sed -i -e 's/\r$//' force && screen -S setup ./force
```
