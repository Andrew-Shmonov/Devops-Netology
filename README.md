# Devops-Netology

#terraform gitignore

# Игнорирует все файлы, что содержатся в папке .terraform не важно насколько большая вложенность директории в дереве (игнорирует подпапки).
**/.terraform/*

# Игнорирует файлы с расширнием .tfstate и файлы с частью наименования .tfstate с любым расширением, к примеру, ххх.tfstate.backup
*.tfstate
*.tfstate.*

# Игнорирует файл crash.log
crash.log

# Игнорирует файл с расширением .tfvars
*.tfvars

# Игнорирует файлы override.tf и override.tf.json, а так же файлы содержащие в наименовании часть _override.tf или _override.tf.json
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Игнорирует файлы .terraformrc и terraform.rc
.terraformrc
terraform.rc