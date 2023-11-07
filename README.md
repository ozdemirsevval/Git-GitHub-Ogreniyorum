# Git&GitHub Öğrenirken Tuttuğum Notlar

Git Komutları

git init : Bu komut ile proje dizininizde GIT dizinini oluşturur. Bu dizinde projenizin repo adresi, projenin akışı, bilgileri gibi veriler bulunur.

git add :  Verilen paremetrelere göre o dosyaları dizine ekler ve commit’lemeye hazır hale gelirler. “Git add .” komutu mevcut dizindeki tüm dosyaları dizine ekler. “Git add dosya.txt” komutu mevcut dizindeki “dosya.txt” dosyasını dizine ekler. (git add README.md gibi)

git rm (remove) : git add komutunun tersi olarak belirtiğiniz dosya veya dosyaları çalışma dizininden siler. (git rm README.md)

git commit : git commit -m “ilk commit” komutu çalıştırdığımızda “ilk commit” başlığıyla o anki çalışma dizinindeki dosyaları .git içindeki özel bir bölüme(head) ekler.

git status : Proje dosyalarının o anki durumu hakkında bilgi verir. Durumu değiştirilmiş dosyaları gösterir.

git branch : Bu komut, geçerli depodaki tüm yerel dalları listeler. *git branch [branch name] Bu komut yeni bir dal oluşturur. (git branch -M main)

git remote : Bu komut, yerel deponuzu uzak sunucuya bağlamak için kullanılır. git remote add [variable name] [Uzak Sunucu Linki] (git remote add origin git@github.com:ozdemirsevval/first-repos.git)

git push : Bu komut, ana dalın taahhüt edilen değişikliklerini uzak havuzunuza gönderir. (git push -u origin main)