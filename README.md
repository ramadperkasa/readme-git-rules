## Deskripsi Branch
Terdapat beberapa branch dengan detail sebagai berikut:
Nama Branch  | Deskripsi
------------- | -------------
main  | branch untuk production
staging  | branch untuk server client
dev  | branch untuk server developmet

## Git Commit Convention

Bekerja dengan *atomic git commits, *berarti commit Anda berukuran sekecil mungkin. Setiap komit melakukan satu, dan hanya satu hal sederhana, yang dapat diringkas dalam kalimat sederhana. Jumlah perubahan kode tidak masalah.

beberapa contoh untuk melakukan pesan:


feat(name of feature): Jelaskan apa yang terjadi pada perubahan ini. ref(#FEATURE001)



fix(name of feature): Jelaskan apa yang terjadi pada perubahan ini. ref(#ISSUE001).


# Git Branch Convention

Gunakan awalan *feature/* saat mengerjakan fitur DAN *fixing/* saat Anda memperbaiki masalah.

beberapa contoh untuk nama cabang:

feature/master-karyawan



fixing/error-on-create-employee


# Merge Request Convention

Saat membuat merge request di platform gitlab, ada beberapa informasi yang perlu Anda masukkan diantaranya:

### Title

Isikan judul dengan ringkasan perubahan. contoh: *Create employee module*

### Description

Isikan informasi perubahan yang lebih detail dan langkah-langkah yang perlu disesuaikan jika ada. contoh:


- Create an employee page. ref(#FEATURE001)
- Added the authorization process on the employee page. ref(#FEATURE002)

Notes: Please install library before deploy.



Catatan: Harap *pisahkan* MR untuk fitur dan hotfix agar memudahkan proses pelacakan perubahan di masa mendatang.
