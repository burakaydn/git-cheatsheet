* **Yeni bir kod deposu oluşturma**
> git init

* **Git konfigürasyonu**
> git config –global user.name “GDG Ankara”
> git config --global user.email "eposta@dresi.com"

* **Değişiklikleri indekse ekleme**
> git add .

* **Kod deposu durumu**
> git status

* **Değişiklikleri kaydetme**
> git commit -m "Why?"

* **Uzak kod deposu ekleme**
> git remote add remote_repo_name remote_repo_path

* **Değişiklikleri uzak kod deposuna gönderme**
> git push remote_repo local_branch

* **Kod deposunu klonlama**
> git clone repository_path

* **Yerel kod deposunu uzak depodan güncelleme**
> git pull

* **Dalları listeleme**
> git branch

* **Yeni bir dal oluşturma**
> git checkout -b branch_name

* **Dal değiştirme**
> git checkout branch_name

* **Dal silme**
> git branch -d branch_name

* **Dal birleştirme**
> git merge otherbranch

* **Dosyayı depoya eklenen son haline geri çevirme**
> git checkout -- File.java

* **Değişiklikleri görme**
> git diff

* **Bir önceki kayıtlı duruma dönme**
> git reset

* **Indeksten dosyayı kaldırma**
> git rm File.java

* **İzlenmeyen dosyaları kaldırma**
> git clean -f

* **Depo dışında tutulan dosyaları kaldırma**
> git clean -f -X
