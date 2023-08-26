# Temel Komutlar
`mkdir`: Klasör yaratmak için kullanılır.
```console
[fuatsezer@localhost prod_level]$ mkdir linux_basic
```
`cd`: bulunduğun dizini değiştirmek için kullanılır.
```console
[fuatsezer@localhost prod_level]$ cd linux_basic/
```
`cd ..`: alt dizine geçmek için kullanılır.
```console
[fuatsezer@localhost prod_level]$ cd ..
```
`pwd`: bulunduğun dizini dödürür.
```console
[fuatsezer@localhost notes]$ pwd
/home/fuatsezer/prod_level/linux_basic/notes
```
`ls`: bulunduğun dizinde neler olduğunu döndürür.
```console
[fuatsezer@localhost linux_basic]$ ls
notes
```
`ls -l`: bulunduğun dizinde neler olduğunu daha detaylı gösterir.
```console
[fuatsezer@localhost ~]$ ls -l
toplam 0
drwxr-xr-x. 2 fuatsezer fuatsezer  6 Ağu 20 20:20 Belgeler
drwxr-xr-x. 2 fuatsezer fuatsezer  6 Ağu 20 20:20 Downloads
```
`ctrl + l` veya `clear`: terminali temizler.

`ls -la`: bulunduğun dizinde neler olduğunu (gizli dosyalar dahil) daha detaylı gösterir.
```console
[fuatsezer@localhost ~]$ ls -la
toplam 0
drwxr-xr-x. 2 fuatsezer fuatsezer  6 Ağu 20 20:20 Belgeler
drwxr-xr-x. 2 fuatsezer fuatsezer  6 Ağu 20 20:20 Downloads
```
`history 10`: yazılan son 10 komutu döndürür.

```console
[fuatsezer@localhost ~]$ history 10
    4  cd linux_basic/
    5  mkdir notes
    6  cd notes/
    7  pwd
    8  ls
    9  cd ..
   10  ls
   11  cd ~
   12  ls -l
   13  history 10
```
`alias`: Sık kullanılan komutlara kısaltma verir.
```console
[fuatsezer@localhost linux_basic]$ alias ml="echo \"merhaba linux\""
[fuatsezer@localhost linux_basic]$ ml
merhaba linux
```


