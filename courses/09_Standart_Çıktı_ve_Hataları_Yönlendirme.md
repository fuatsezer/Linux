# Standart Çıktı ve Hataları Yönlendirme
`>` aktarır

`>>` üzerine yazar

`&>` hataları yazar.

`&>>` hataları üzerine yazar.
`EOF` consola yazılanı dosyaya yazar.
```console
[fuatsezer@localhost notes]$ head -n 5 words.txt > output_directed
[fuatsezer@localhost notes]$ echo "This is new line" >> output_directed
[fuatsezer@localhost notes]$ ls -l mahmut &>> output_directed
[fuatsezer@localhost notes]$ cat <<EOF > sortfile.txt
> ali,33
> mahmut,25
> cemal,41
> gizem,27
> burcu,33
> zeynep,29

```
