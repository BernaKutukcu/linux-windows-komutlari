# Linuxta En Sık Kullanılan 50+ Komut
Bu dosyada Linux işletim sisteminde sıkça kullanılan komutlar ve açıklamaları listelenmiştir.

## 📁 Dosya ve Klasör İşlemleri

- `ls` : Bulunduğun dizindeki dosyaları listeler.                 

- `ls -l` : Detaylı listeleme yapar.

- `ls -a` : Gizli dosyaları da gösterir.

- `pwd` : Geçerli dizinin yolunu gösterir.

- `cd` : Dizin değiştirir. (cd .. → bir üst dizine gider)

- `mkdir` : Yeni klasör oluşturur.

- `rmdir` : Boş klasör siler.

- `rm` : Dosya siler. (rm -r → klasör ve içeriğini siler)

- `cp` : Dosya veya klasörü kopyalar.

- `mv` : Dosyayı taşır veya adını değiştirir.

- `touch` : Yeni boş dosya oluşturur.

## 🔍 Dosya Görüntüleme ve Arama

- `cat` : Dosya içeriğini terminalde gösterir.

- `more` : Dosyayı sayfa sayfa görüntüler.

- `less` : Daha gelişmiş sayfalama sağlar (yukarı-aşağı gezinme).

- `head` : Dosyanın ilk satırlarını gösterir.

- `tail` : Dosyanın son satırlarını gösterir.

- `grep` : Dosya içinde metin arar.

- `find` : Belirli dosya veya klasörleri arar.

- `locate` : İsimle hızlı dosya araması yapar.

- `wc` : Kelime, satır ve karakter sayısını gösterir.

- `diff` : İki dosya arasındaki farkları karşılaştırır.

## ⚙️ Sistem Bilgisi ve Yönetimi

- `uname -a` : Sistem bilgilerini gösterir.

- `df -h` : Disk kullanımını gösterir.

- `du -h` : Dosya veya klasörün boyutunu gösterir.

- `free -h` : RAM kullanımını gösterir.

- `top` : Çalışan işlemleri canlı olarak gösterir.

- `htop` : Gelişmiş süreç izleme (önceden kurulu olmayabilir).

- `ps` : Çalışan süreçleri listeler.

- `kill` : Süreç ID’sine göre işlemi sonlandırır.

- `uptime` : Sistemin ne zamandır açık olduğunu gösterir.

- `history` : Önceden girilen komutları listeler.

## 🌐 Ağ Komutları

- `ping` : Ağ bağlantısını test eder.

- `ifconfig` : Ağ arayüzlerini gösterir (yeni sistemlerde ip addr).

- `ip addr` : IP adreslerini ve ağ ayarlarını gösterir.

- `netstat` : Aktif bağlantıları ve portları gösterir.

- `curl` : Web istekleri yapar (örneğin curl google.com).

- `wget` : İnternetten dosya indirir.

- `scp` : Uzak makineye dosya kopyalar.

- `ssh` : Uzak sunucuya bağlanır.

- `traceroute` : Paketin geçtiği yönlendiricileri gösterir.

- `nslookup` : DNS sorgusu yapar.

## 🔒 Yetki ve Kullanıcı Yönetimi

- `sudo` : Komutu yönetici (root) olarak çalıştırır.

- `su` : Root veya başka bir kullanıcıya geçiş yapar.

- `adduser` : Yeni kullanıcı ekler.

- `passwd` : Kullanıcının şifresini değiştirir.

- `chmod` : Dosya/klasör izinlerini değiştirir.

- `chown` : Sahipliği değiştirir.

- `groups` : Kullanıcının ait olduğu grupları listeler.

## 🧰 Paket Yönetimi (Dağıtıma Göre Değişir)

### Debian/Ubuntu:

- `apt update` : Paket listesini günceller.

- `apt upgrade` : Güncellemeleri yükler.

- `apt install` : Yeni paket kurar.

- `apt remove` : Paketi kaldırır.

### RedHat/CentOS:

- `yum install` : Paket yükler.

- `dnf update` : Yeni nesil paket yöneticisiyle günceller.

## 🔌 Diğer Faydalı Komutlar

- `clear` : Ekranı temizler.

- `echo` : Terminale metin yazdırır.

- `man` : Komutun kullanım kılavuzunu açar.

- `reboot` : Sistemi yeniden başlatır.

- `shutdown now` : Bilgisayarı hemen kapatır.

- `exit` : Terminal oturumunu kapatır.