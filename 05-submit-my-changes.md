Simulasikan bagaimana proses kita dalam melakukan clone suatu project pada GitHub hingga melakukan Pull Request untuk perubahan yang ingin kita submit.

1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu
   - gh repo fork (link gh)
2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
   - gh repo clone (link gh)
3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
   - git branch (nama branch baru)
4. Checkout ke dalam branch tersebut yang telah kamu buat
   - git checkout (nama brach baru)
5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
   - touch (nama).md
6. Isi file tersebut davidwinalda.md dengan konten di bawah ini:
   > Nama Lengkap: David Winalda
   > Umur: 27
   > Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang
   - nano (nama).md
7. Masukkan file .md tersebut ke dalam staging area
   - git add (nama).md
8. Commit dengan memberikan pesan nama file .md kamu
   - git commit -m "nama file.md"
9. Merge branch yang telah kamu buat ke dalam branch master
   - git merge (namabranchbaru)
10. Push ke dalam branch master
   - git push -u origin master
11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.
   - Pull request
