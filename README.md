<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=40&duration=4&pause=20&color=6D26BFFF&center=true&vCenter=true&width=482&lines=Kali+Linux" alt="kali" />

### **1. Install Node.js and npm** 🎉

1. **Update package list**:
   ```bash
   sudo apt update
   ```

2. **Install Node.js and npm**:
   ```bash
   sudo apt install nodejs npm
   ```


3. **Verify installation**:
   ```bash
   node -v
   npm -v
   ```

### **2. Install PHP** 🎖️

1. **Install PHP**:
   ```bash
   sudo apt install php php-cli php-fpm php-mysql
   ```

2. **Verify PHP installation**:
   ```bash
   php -v
   ```

### **3. Install Composer (PHP Dependency Manager)** 🔥

1. **Download Composer Installer**:
   ```bash
   curl -sS https://getcomposer.org/installer | php
   ```

2. **Move Composer to a global location**:
   ```bash
   sudo mv composer.phar /usr/local/bin/composer
   ```

3. **Verify Composer installation**:
   ```bash
   composer -v
   ```

### **4. Install Visual Studio Code (VSCode)** 😎

1. **Install dependencies** (if not installed earlier):
   ```bash
   sudo apt install software-properties-common apt-transport-https curl
   ```

2. **Add Microsoft GPG key**:
   ```bash
   sudo curl https://packages.microsoft.com/keys/microsoft.asc | sudo gpg --dearmor -o /usr/share/keyrings/microsoft-archive-keyring.gpg
   ```

3. **Add the VSCode repository**:
   ```bash
   echo "deb [signed-by=/usr/share/keyrings/microsoft-archive-keyring.gpg] https://packages.microsoft.com/repos/vscode stable main" | sudo tee /etc/apt/sources.list.d/vscode.list
   ```

4. **Update package list and install VSCode**:
   ```bash
   sudo apt update
   sudo apt install code
   ```

5. **Launch VSCode**:
   ```bash
   code
   ```

### **5. Install Google Chrome** 🚨

1. **Download Google Chrome**:
   ```bash
   wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
   ```

2. **Install Google Chrome**:
   ```bash
   sudo apt install ./google-chrome-stable_current_amd64.deb
   ```

3. **Verify installation**:
   ```bash
   google-chrome-stable --version
   ```

### **6. Install MySQL Workbench (for Database Management)** ☠️

1. **Install MySQL Workbench**:
   ```bash
   sudo apt install mysql-workbench
   ```

2. **Launch MySQL Workbench**:
   ```bash
   mysql-workbench
   ```

### **7. Install SQL Database (MariaDB or MySQL)** 

1. **Install MariaDB (if not already installed)**:
   ```bash
   sudo apt install mariadb-server mariadb-client
   ```

2. **Start MariaDB service**:
   ```bash
   sudo systemctl start mariadb
   sudo systemctl enable mariadb
   ```

3. **Secure the MariaDB installation**:
   ```bash
   sudo mysql_secure_installation
   ```

4. **Log into MySQL or MariaDB**:
   ```bash
   sudo mysql -u root -p
   ```

---

### **Summary of Installed Tools:**

1. **Node.js & npm**: JavaScript runtime and package manager.
2. **PHP**: Server-side scripting language.
3. **Composer**: Dependency manager for PHP.
4. **VSCode**: Code editor.
5. **Google Chrome**: Web browser.
6. **MySQL Workbench**: Database management tool.
7. **MariaDB/MySQL**: SQL database server.
```
