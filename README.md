# Create new touch

**/.terraform/*   Все вложенные катологи с расширение terraform и после будут игнорированы
!
*.tfstate   Все вложение с расширением tfstate будут с игнорированы

*.tfstate.* Все вложение с название tfstate и любой символ
crash.log Все название и crash с расширениес log будут игнорированы

crash.*.log Все название и crash с вложение и расширением log будут игнорированы
!
*.tfvars    Ве вложение с расширением tfvars будут игнорированы

*.tfvars.json   Все вложение с название tfvars и расширением json будут игнорированы
!
override.tf Все название  override с расширениеь tf будут игнорированы

override.tf.json    Все название override и вложение tf с расширением tf будут игнорированы

*_override.tf   Любое вложение с нижнем подчеркиванием и название override с расширением tf будут игнорированы

*_override.tf.json Любое вложение с нижнем подчеркиванием и название override с вложением tf и расширением json 
будут игнорированы
!
.terraformrc  Любое одно значение с раширением terraformrc будут игнорированы

terraform.rc Название terraform с расширением rc будут игнорированы

hi friends
