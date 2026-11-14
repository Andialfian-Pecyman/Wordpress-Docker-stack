# 🚀 Deployment wordpress dengan menggunakan docker compose 

Repository ini berisi konfigurasi pada 'docker-compose.yml' untuk instance **Wordpress** dengan menggunakan database **Mariadb** secara lokal atau  di server 

---

## 🛠️ Requirement 
Sebelum melakukan deploy pastikan untuk setup berikut ini sudah ada dan pastikan sudah running 
* [Ubuntu](https://ubuntu.com/download/server)(26.04.1 LTS)
* [Docker](https://docs.docker.com/engine/install/ubuntu/)(29.9.2 /latest)
* [Cloudflare-tunnel](https://developers.cloudflare.com/tunnel/)

---

## 📁 struktur file
'''your-wordpress-folder
├── docker-compose.yaml
├── html/
│   └── myweb
├── conf.d/
│   └── default.conf.template
├── logs/
│   └── nginx
└── README.md