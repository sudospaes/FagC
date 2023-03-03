# FagC : Fast get certificate script with Acme

## How to install and use it

1. Switch to root
```
su
cd
```

2. Install curl and socat on your linux :
```diff
For Redhat Base : yum install curl socat or dnf install curl socat

For Debian Base : apt install curl socat
```

3. Download FagC script :
```
curl -LO https://raw.githubusercontent.com/sudospaes/FagC/main/fagc
```

4. Run FagC script :
```
chmod +x fagc
sh fagc
```
