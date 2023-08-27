# Grep ile Düzenli ifadeler
`[fuatsezer@localhost notes]$ grep -in  ^mur words.txt`: Mur ile başlayanları bulma

`[fuatsezer@localhost notes]$ grep -in kuş$ words.txt`: kuş ile bitenleri bulma

`[fuatsezer@localhost notes]$ grep -in "k.ş" words.txt`: içinde k ile başlayan ş ile biten orta harf herhangi birşey olabilir bu 3 harf kombinasyonu olanları bulma.

`[fuatsezer@localhost notes]$ grep -in "k.ş$" words.txt`: k.ş ile bitenleri bulma

`[fuatsezer@localhost notes]$ grep -in bak  words.txt`: içinde bak olanları bulma
