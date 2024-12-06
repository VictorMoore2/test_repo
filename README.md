# Install Components

# Install Apache
sudo apt update:
sudo apt install apache2 
sudo systemctl start apache2
sudo systemctl enable apache2
sudo systemctl status apache2


# Install MySQL
sudo apt install mysql-server
sudo mysql_secure_installation

# Installation of PHP for apache2
sudo apt install php libapache2-mod-php php-mysql 


# Install PHP and PHP-FPM
sudo apt install php-fpm php-mysql php-cli php-cli php-common php-curl php-xml php-mbstring

