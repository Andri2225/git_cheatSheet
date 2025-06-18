# create 
    git init                <= menginisialisasi repository
    git clone               <= mendownload/cloning repository dari github
# membuat perubahan
git add nama_file                                                       <= memasukkan file ke history, supaya perubahan yg dilakukan dicatat oleh history git
    git add .                                                           <= sama aja cuma, langsung sekaligus
    git commit -m "penjelasan apa yang kamu ubah/tambahkan"             <= memberi tahu apa apa saja yang telah dilakukan 
    git reset                                                           <= membatalkan track perubahan dalam history ketika lu ga jadi mau commit sebuah file
    git reset --hard                                                    <= sama aja intinya file yg seblumnya di track jadi nggak ke track lagi
    git commit -m "pesan"                                               <= tujuannya memastikan perubahan yang kita lakukan tercatat dalam history & ada penjelasan singktnya juga
    git diff                                                            <= melihat perubahan dalam file
    git show HEAD                                                       <= melihat perubahan dalam file di commit terakhir
#












###### TROUBLESHOOT jika error saat melakukan commit
kamu bisa coba setting username dan email lu dulu.


git config --global user.name "namaLu"
git config --global user.email "jasonsmit0032a@gmail.com"
