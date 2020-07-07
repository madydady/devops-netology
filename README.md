# devops-netology

В каталог terraform добавлен файл .gitignore. В файле перечислены файлы и каталоги, которые будут проигнорированы Git:
- все каталоги с названием .terraform и вложенные в них файлы
- все файлы с расширением .tfstate и файлы вида [foo].tfstate.[bar]
- лог-файл с именем crash.log
- все файлы с расширением .tfvars
- файлы override.tf, override.tf.json и все файлы, имена которых заканчиваются на _override.tf или _override.tf.json
- файлы .terraformrc и terraform.rc



