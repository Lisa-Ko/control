Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками, хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла. Переименовать файл, дав ему новое имя (Друзья человека).
Создать директорию, переместить файл туда.
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

Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.
sudo apt устанавливает mysql-сервер, mysql-клиент

Установим пароль sudo mysqladmin password -u root -p

sudo mysql_secure_installation

Попробуем зайти sudo mysql -u root

Установить и удалить deb-пакет с помощью dpkg.
wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j_8.0.32-1ubuntu22.04_all.deb

Устанавливаем пакет mysql-connector-j_8.0.32-1ubuntu22.04_all.deb:

sudo dpkg - i mysql -connector-j_8.0.32-1ubuntu22.04_all.deb

Удаляем пакет и его сопутствующие пакеты:

sudo dpkg -r mysql-connector-j

sudo apt-получить автоматическое удаление

130 cat > 'Домашние животные'

131 ls

132 cat > 'Вьючные животные'

133 cat 'Домашние животные' 'Вьючные животные' > Животные

134 ls

135 cat Животные

136 cat > Животные

137 cat Животные

138 ls

139 cat 'Домашние животные' 'Вьючные животные' > Животные

140 ls

141 cat Животные

142 mv Животные 'Друзья человека'

143 мкдира newdir

144 mv 'Друзья человека' newdir/

145 ls

146 дерево

147 дерево установки sudo apt # версия 2.0.2-1

148 дерево

149 wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb

150 cd Загрузки sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb

151 ls

152 sudo apt-получить

153 компакт -диска с записями/

154 Загрузки компакт-дисков/

155 Загрузок компакт-дисков

156 cd Загрузки

157 ...

158 компакт-дисков..

159 компакт-дисков../

160 компакт - дисков ../

161 cd Загрузки sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb

162 cd 'Загрузки' sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb

163 cd Загрузки

164 sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb

165 компакт - дисков ../

166 sudo apt-получить, удалить --очистить mysql*

167 обновление sudo apt

168 sudo apt устанавливает mysql-сервер mysql-клиент

169 sudo dpkg -i ~/Загрузки/mysql-apt-config

170 sudo apt устанавливает mysql-сервер mysql-клиент

171 пароль sudo mysqladmin -u root -p

172 mysql_secure_installation

173 установка sudo mysql_secure_installation

174 mysql -u root -p

175 пароль sudo mysqladmin -u root -p

176 mysql -u root -p

177 sudo mysql -u root

178 ИЗМЕНИТЕ ПОЛЬЗОВАТЕЛЯ 'root'@ 'localhost', ИДЕНТИФИЦИРОВАННОГО С ПОМОЩЬЮ mysql_native_password, НА 'new-password'

179 sudo mysql -u root -p

180 Вт https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j_8.0.32-1ubuntu22.04_all.deb

181 sudo dpkg - i mysql -connector-j_8.0.32-1ubuntu22.04_all.deb

182 udo dpkg -r mysql-connector-j

183 sudo dpkg -r mysql-connector-j

184 sudo dpkg - i mysql -connector-j_8.0.32-1ubuntu22.04_all.deb

185 sudo apt-получить автозапуск

186 история
