//buat awal
git clone
composer install
npm install
npm run dev //jaga jaga
cp .env.example .env
ganti nama database di .env
buat database sesuai nama tadi
php artisan key:generate
php artisan migrate //kalo udah ada migration di laravelnya
php artisan storage:link //kalo codingan udah pake storage:link

//mulai ngoding
git fetch
git pull //if needed
git branch nama_branch //biar ga ngeganggu branch main
git checkout nama_branch

//selesai ngoding
git add .
git commit -m "keterangan nambah apa"
git checkout main
git fetch
git pull //if needed
git merge nama_branch (bisa jadi ada 
git push
git branch -d nama_branch //buat ngehapus branch lokal

//yang harus dilakuin setiap saat(bisi ada yang nambah update di origin/main)
git checkout main //kalo ga di branch main
git fetch
git pull //kalo ada update