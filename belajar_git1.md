Hallo saya sedang belajar git

#configurasi Git
## Lihat confiugarsi global
	git config --global list--

## Set configurasi nama user dan email
	git config --global user.name "nama"
	git config --global user.email "nama email"

## hapus config
	git config --unset user.name
	git config --unset user.email
atau
	git config --global --edit

## Membuat repository GIT (Membuat Project GIT)
## Cara 1
	git init nama-project (nama project akan jadi sebuah folder)
## Cara 2
	Buka folder projetc
	ketik: git init .

## Membuat repository GIT untuk project yang sudah ada
	Buka folder project ynag sudah dibuat
	Ketikan git init . dalam terminal
	
## Mencatat Perubahan

