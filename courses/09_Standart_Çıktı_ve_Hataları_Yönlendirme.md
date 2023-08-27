# Standart Çıktı ve Hataları Yönlendirme
`>` aktarır
`>>` üzerine yazar
`&>` hataları yazar.
`&>>` hataları üzerine yazar.
```console
[fuatsezer@localhost notes]$ head -n 5 words.txt > output_directed
[fuatsezer@localhost notes]$ echo "This is new line" >> output_directed
[fuatsezer@localhost notes]$ ls -l mahmut &>> output_directed

```
