## 1 в терминале операционной системы Linux, создать два файла
___
*cat > ДомашниеЖивотные*

собаки

кошки

хомяки

*cat > ВьючныеЖивотные*

лошади

верблюды

ослы

*cat ДомашниеЖивотные ВьючныеЖивотные > ДрузьяЧеловека*

*cat ДрузьяЧеловека*

## 2 Создать директорию, переместить файл туда.
___
*mv ДрузьяЧеловека Животные*

## 3 Подключить дополнительный репозиторий MySQL. 
# Установить любой пакет из этого репозитория.
___

*sudo apt install mysql-server mysql-client*

*sudo apt-get update*

## 4 Установить и удалить deb-пакет с помощью dpkg
___

# Установка

*wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb*

*sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb*

*sudo apt install mysql-server*

*sudo mysql_secure_installation*

*sudo mysql_secure_installation*

*sudo apt-get install mysql-workbench-community*

# Удаление

*sudo dpkg -s mysql-server*

*sudo dpkg -r mysql-workbench-community*

*sudo dpkg -r mysql-community-server*