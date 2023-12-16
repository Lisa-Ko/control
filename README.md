1. Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы), а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека).
2. Создать директорию, переместить файл туда.
   
 cat > 'Домашние животные'
Собаки
Кошки
Хомяки
cat > 'Вьючные животные'
Лошади
Верблюды
Ослы
cat 'Домашние животные' 'Вьючные животные' > Животные
mv Животные 'Друзья человека'
ls
mkdir newdir
mv 'Друзья человека' newdir/
ls

4. Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.

sudo apt install mysql-server mysql-client
Установим пароль sudo mysqladmin password -u root -p
sudo mysql_secure_installation
Попробуем зайти sudo mysql -u root
6. Установить и удалить deb-пакет с помощью dpkg.
   
Скачиваем пакет для установки:
wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
Устанавливаем пакет mysql-connector-j_8.0.32-1ubuntu22.04_all.deb:
sudo dpkg - i mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
Удаляем пакет и его сопутствующие пакеты:
sudo dpkg -r mysql-connector-j
sudo apt-получить автоматическое удаление

  130  cat > 'Домашние животные'
  131  ls
  132  cat > 'Вьючные животные'
  133  cat 'Домашние животные' 'Вьючные животные' > Животные
  134  ls
  135  cat Животные
  136  cat > Животные
  137  cat Животные
  138  ls
  139  cat 'Домашние животные' 'Вьючные животные' > Животные
  140  ls
  141  cat Животные
  142  mv Животные 'Друзья человека'
  143  mkdir newdir
  144  mv 'Друзья человека' newdir/
  145  ls
  146  tree
  147  sudo apt  install tree  # version 2.0.2-1
  148  tree
  149  wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb
  150  cd Загрузки sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb
  151  ls
  152  sudo apt-get 
  153  cd Downlosds/
  154  cd Downloads/
  155  cd Downloads
  156  cd Загрузки
  157  ...
  158  cd..
  159  cd../
  160  cd ../
  161  cd Загрузки sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb
  162  cd 'Загрузки' sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb
  163  cd Загрузки
  164  sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb
  165  cd ../
  166  sudo apt-get remove --purge mysql*
  167  sudo apt update
  168  sudo apt install mysql-server mysql-client
  169  sudo dpkg -i ~/Загрузки/mysql-apt-config
  170  sudo apt install mysql-server mysql-client
  171  sudo mysqladmin password -u root -p
  172  mysql_secure_installation
  173  sudo mysql_secure_installation
  174  mysql -u root -p
  175  sudo mysqladmin password -u root -p
  176  mysql -u root -p
  177  sudo mysql -u root
  178  ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'new-password'
  179  sudo mysql -u root -p
  180  wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
  181  sudo dpkg - i mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
  182  udo dpkg -r mysql-connector-j
  183  sudo dpkg -r mysql-connector-j
  184  sudo dpkg - i mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
  185  sudo apt-get autoremovу
  186  history



