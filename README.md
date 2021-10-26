```
termux-setup-storage
```
```
pkg update
```
```
pkg upgrade 
```
```
pkg install python
```
```
pip install --upgrade pip
```
```
pkg install git
```
```
mkdir /sdcard/fclone/ -p
```
```
cd
```
```
git clone https://github.com/phoethar1/fclone_android
```
```
mv fclone_android/fclone /data/data/com.termux/files/usr/bin/
```
```
chmod 777 /data/data/com.termux/files/usr/bin/fclone
```
```
mv fclone_android/fc.py /sdcard/fclone/
```
```
fclone version
```



-   fclone folder ထဲ accounts folder ကို copy ကူးလာထည့်

-   accounts folder ထဲက ကြိုက်တယ့်json file တခုကို `1.json` လို့ Rename လုပ်

-   fclone  ကို run ရင်
```
cd /sdcard/fclone
```
```
python fc.py
```
     





