# NiRos-Template
### راهنما هست تو خود کد و میتونید راحت شخصی سازی کنید❤️
### در لاین 253 میتونید کلمه  NiRos رو تغییر دهید
### Template for rebecca and marzban panel
![Preview](https://github.com/Deepside-607/NiRos-Template/blob/main/IMG_20251220_001353_568.jpg?raw=true)
### مرزبان:  
### ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/Deepside-607/NiRos-Template/main/index.html
```
### سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

### سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
marzban restart
```

-----------------------

### ربکا:  
### ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://raw.githubusercontent.com/Deepside-607/NiRos-Template/main/index.html
```
### سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

### سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
rebecca restart
```


