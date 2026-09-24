First add line text


Будут проигнорированы:

папка с кэшем и рабочими данными .terraform/;
файлы состояния инфраструктуры, которые имеют расширение .tfstate или символы в имени tfstate.* с любым расширением;
конкретный файл с именем crash.log или файлы, имеющие символы в имени crash.*.log;
файлы с переменными с расширением .tfvars или tfvars.json;
файлы override.tf, override.tf.json, также файлы оканчивающиеся на _override.tf или _override.tf.json;
временный файл блокировки состояния .terraform.tfstate.lock.info;
файлы конфигурации CLI Terraform .terraformrc и terraform.rc.
