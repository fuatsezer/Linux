## Değişkenler
`env`: Ortamdaki değişkenleri gösterir.
```console
[fuatsezer@localhost ~]$ env
```
* **Not:Değişkenler büyük harfler ile tanımlanır**
```console
[fuatsezer@localhost ~]$ MY_NAME=Fuat
[fuatsezer@localhost ~]$ echo $MY_NAME
```
`export`: Global değişken tanımlamak için kullanılır.
```console
[fuatsezer@localhost ~]$ export MY_NAME
[fuatsezer@localhost ~]$ env | grep MY_NAME
MY_NAME=Fuat
```
`unset`: Global değişkeni silmek için kullanılır.
```console
[fuatsezer@localhost ~]$ unset MY_NAME
```
