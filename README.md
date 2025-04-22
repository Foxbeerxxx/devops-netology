# devops-netology
# Домашнее задание к занятию "`Git`" - `Татаринцев Алексей`

### Задание 1

1. `Регистрация на github уже есть`

![1](https://github.com/Foxbeerxxx/devops-netology/blob/main/img/1.png)`

2. `Создаем репозиторий на Github`

![2](https://github.com/Foxbeerxxx/devops-netology/blob/main/img/2.png)`


3. `Задаю имя и почту , проверяю статус`
![3](https://github.com/Foxbeerxxx/devops-netology/blob/main/img/3.png)`

4. `Проверяю команду git diff`

![4](https://github.com/Foxbeerxxx/devops-netology/blob/main/img/4.png)`



5. `В Каталоге terraform создаю .gitignore файл и заполняю его, как итог будут проигнорированы описанные там файлы`

```
# Local .terraform directories
**/.terraform/*

# .tfstate files
*.tfstate
*.tfstate.*

# Crash log files
crash.log
crash.*.log

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
*.tfvars
*.tfvars.json

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Ignore transient lock info files created by terraform apply
.terraform.tfstate.lock.info

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc
terraform.rc
```

6. `Проверяем git log`

![5](https://github.com/Foxbeerxxx/devops-netology/blob/main/img/5.png)`


