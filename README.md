1.
echo "dog, cat, hamster" > pets
echo "horse, camel, donkey" > Pack\ animals
cat pets Pack\ animals > animals
mv animals Human\ Friends
2.
mkdir testdir
mv Human\ Friends testdir/
3.
sudo apt update
wget https://dev.mysql.com/get/mysql-apt-config_0.8.28-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.28-1_all.deb
sudo apt-get update
sudo apt-get install -y mysql-server
4.
wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j_8.2.0-1ubuntu22.04_all.deb
sudo dpkg -i mysql-connector-j_8.2.0-1ubuntu22.04_all.deb
sudo dpkg -r mysql-connector-j
sudo apt-get autoremove
5.
![Консоль](Images/1.png)
