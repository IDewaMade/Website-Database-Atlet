//buat awal <br>
git clone <br>
composer install<br>
npm install<br>
npm run dev //jaga jaga<br>
cp .env.example .env<br>
ganti nama database di .env<br>
buat database sesuai nama tadi<br>
php artisan key:generate<br>
php artisan migrate //kalo udah ada migration di laravelnya<br>
php artisan storage:link //kalo codingan udah pake storage:link<br>

//mulai ngoding<br>
git fetch<br>
git pull //if needed<br>
git branch nama_branch //biar ga ngeganggu branch main<br>
git checkout nama_branch<br>

//selesai ngoding<br>
git add .<br>
git commit -m "keterangan nambah apa"<br>
git checkout main<br>
git fetch<br>
git pull //if needed<br>
git merge nama_branch (bisa jadi ada conflict)<br>
git push<br>
git branch -d nama_branch //buat ngehapus branch lokal<br>

//yang harus dilakuin setiap saat(bisi ada yang nambah update di origin/main)<br>
git checkout main //kalo ga di branch main<br>
git fetch<br>
git pull //kalo ada update<br>
