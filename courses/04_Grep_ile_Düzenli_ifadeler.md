# Grep ile Düzenli ifadeler
`[fuatsezer@localhost notes]$ grep -in  ^mur words.txt`: Mur ile başlayanları bulma

`[fuatsezer@localhost notes]$ grep -in kuş$ words.txt`: kuş ile bitenleri bulma

`[fuatsezer@localhost notes]$ grep -in "k.ş" words.txt`: içinde k ile başlayan ş ile biten orta harf herhangi birşey olabilir bu 3 harf kombinasyonu olanları bulma.

`[fuatsezer@localhost notes]$ grep -in "k.ş$" words.txt`: k.ş ile bitenleri bulma

`[fuatsezer@localhost notes]$ grep -in bak  words.txt`: içinde bak olanları bulma

`[fuatsezer@localhost notes]$ grep M[au]k  words.txt`: M ile başlasın a veya u ile devam etsin k ile biten 3 harfli bir kombinasyon ile başlayanları bulma

`[fuatsezer@localhost notes]$ grep M[^ae]k  words.txt`: M ile başlasın a veya e ile devam etmeyen k ile biten 3 harfli bir kombinasyon ile başlayanları bulma

`[fuatsezer@localhost notes]$ grep [111] sample_tc_kimlik_names_numbers.txt`: içinde üç tane 1 olanları bulma.

`[fuatsezer@localhost notes]$ grep [0-4] sample_tc_kimlik_names_numbers.txt`: 0 ile 4 arasında herhangi bir değer olanları bulma.

`[fuatsezer@localhost notes]$ grep [^0-9] sample_tc_kimlik_names_numbers.txt`: içinde rakam olmayanları bulma.

`[fuatsezer@localhost notes]$ grep "[0-9]\{11\}" sample_tc_kimlik_names_numbers.txt`: tc kimlik numaralarını yakalayan pattern

`[fuatsezer@localhost notes]$ grep "[a-zA-Z]\{6\}" sample_tc_kimlik_names_numbers.txt` 6 karakterli isimleri bulma

Not: -v optionı paternin tersini getirir.

`[fuatsezer@localhost notes]$ grep "^Ak\|ş$" words.txt` Ak ile başlayan yada ş ile bitenleri bulma

`[fuatsezer@localhost notes]$ grep "^Ak.*ş$" words.txt` Ak ile başlayan ve ş ile bitenleri bulma
