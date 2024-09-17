Node.JS REQUIRED!!

```bash
git clone https://github.com/WP1223/yescoin.git
cd yescoin 
```
Jalankan perintah berikut untuk menginstal modul yang diperlukan

```bash
npm install
``` 
kalo ada eror `npm init -y` lalu ulangi lagi `npm install`,

```bash
npm install axios
npm install colors
npm install https-proxy-agent
```

buat 2 file data.txt dan proxy.txt

Bagi yang menggunakan banyak akun sebaiknya menggunakan proxy (1 akun tidak perlu membuat file proxy.txt)

Proxy format: 
`http://user:pass@ip:port`

format dalam file data.txt 
`query_id=xxxx atau user_id=xxxx`

RUn 
```bash
node yesyes.js
```
