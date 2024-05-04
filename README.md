| No. | Google Dork                                                                  | Description                                                                     |
|-----|------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| 1   | `intitle:"login" site:example.com`                                          | Search for login pages on a specific website for authentication testing.       |
| 2   | `intitle:"sign in" site:example.com`                                        | Search for sign-in pages on a specific website for authentication testing.     |
| 3   | `intitle:"log in" site:example.com`                                         | Search for log-in pages on a specific website for authentication testing.      |
| 4   | `inurl:"/view/index.shtml"`                                                 | Search for vulnerable webcams for network penetration testing.                  |
| 5   | `intitle:"Network Camera" inurl:"login.htm"`                                 | Search for vulnerable devices for network penetration testing.                  |
| 6   | `filetype:xml inurl:config`                                                  | Search for configuration files for identifying potential misconfigurations.    |
| 7   | `inurl:index.php?id=`                                                       | Search for SQL injection vulnerabilities for database penetration testing.      |
| 8   | `inurl:redir=`                                                               | Search for open redirect vulnerabilities for web application testing.           |
| 9   | `inurl:file=`                                                                | Search for file inclusion vulnerabilities for web application testing.          |
| 10  | `intitle:index.of.backup`                                                    | Search for backup files for information disclosure testing.                     |
| 11  | `intitle:"Network Printer" inurl:"port_"`                                    | Search for exposed network printers for potential exploitation.                 |
| 12  | `intitle:"HP Photosmart" inurl:"index.htm"`                                  | Search for HP Photosmart printers with exposed web interfaces.                  |
| 13  | `inurl:"/etc/passwd"`                                                        | Search for the Linux /etc/passwd file, often containing user account info.      |
| 14  | `filetype:ini inurl:flashFXP.ini`                                            | Search for FlashFXP client configuration files for potential credentials.       |
| 15  | `filetype:lic lic intext:key`                                                | Search for license files containing software keys or serial numbers.            |
| 16  | `intitle:"index of" "private key"`                                           | Search for exposed private keys used for secure communication.                  |
| 17  | `intitle:"index of" "admin.conf"`                                            | Search for admin configuration files with potential sensitive information.      |
| 18  | `intitle:"index of" ".htpasswd"`                                             | Search for .htpasswd files containing hashed passwords.                         |
| 19  | `intitle:"index of" ".htaccess"`                                             | Search for .htaccess files containing server configuration directives.          |
| 20  | `intitle:"index of" "ftp.ini"`                                               | Search for FTP client configuration files with potential credentials.          |
| 21  | `intitle:"index of" "sftp-config.json"`                                      | Search for SFTP configuration files containing potential sensitive info.        |
| 22  | `intitle:"index of" "wp-config.php"`                                         | Search for WordPress configuration files with database credentials.            |
| 23  | `intitle:"index of" "database.yml"`                                          | Search for Ruby on Rails database configuration files with credentials.         |
| 24  | `intitle:"index of" ".env"`                                                  | Search for .env files containing environment variables, including secrets.      |
| 25  | `intitle:"index of" "config.php"`                                            | Search for PHP configuration files with potential sensitive information.        |
| 26  | `intitle:"index of" "settings.py"`                                           | Search for Django configuration files with database credentials.                |
| 27  | `intitle:"index of" "application.properties"`                                | Search for Java application configuration files with sensitive data.            |
| 28  | `intitle:"index of" "credentials.xml"`                                       | Search for XML files containing various credentials or sensitive data.           |
| 29  | `intitle:"index of" "web.config"`                                            | Search for ASP.NET web configuration files with sensitive information.          |
| 30  | `intitle:"index of" "jwt.json"`                                              | Search for JSON files containing JWT tokens or secrets.                          |
| 31  | `intitle:"index of" "docker-compose.yml"`                                    | Search for Docker Compose configuration files with potential secrets.            |
| 32  | `intitle:"index of" "jenkins.conf"`                                          | Search for Jenkins configuration files with potential sensitive info.           |
| 33  | `intitle:"index of" "nginx.conf"`                                            | Search for NGINX server configuration files with potential sensitive data.      |
| 34  | `intitle:"index of" "ssh_config"`                                            | Search for SSH client configuration files with potential credentials.           |
| 35  | `intitle:"index of" "server.xml"`                                            | Search for Tomcat server configuration files with potential sensitive data.     |
| 36  | `intitle:"index of" "vhosts.conf"`                                           | Search for Apache virtual host configuration files with sensitive info.         |
| 37  | `intitle:"index of" "application.conf"`                                      | Search for Play Framework application configuration files with secrets.         |
| 38  | `intitle:"index of" "proftpd.conf"`                                          | Search for ProFTPD server configuration files with potential sensitive info.    |
| 39  | `intitle:"index of" "lighttpd.conf"`                                         | Search for Lighttpd server configuration files with potential sensitive data.  |
| 40  | `intitle:"index of" "httpd.conf"`                                            | Search for Apache HTTP server configuration files with sensitive info.          |
| 41  | `intitle:"index of" "shadow"`                                                | Search for shadow files containing user account information on Unix-based systems.|
| 42  | `intitle:"index of" "password"`                                              | Search for password files containing plaintext or hashed passwords.             |
| 43  | `intitle:"index of" "backup"`                                                | Search for backup files with potential sensitive data.                          |
| 44  | `intitle:"index of" "logs"`                                                  | Search for log files with potentially sensitive information.                     |
| 45  | `intitle:"index of" "root"`                                                  | Search for files or directories named "root" with potential sensitive data.     |
| 46  | `intitle:"index of" "bash_history"`                                          | Search for bash history files containing command-line history.                   |
| 47  | `intitle:"index of" "sensitive"`                                             | Search for files or directories named "sensitive" with potential data.           |
| 48  | `intitle:"index of" "confidential"`                                          | Search for files or directories named "confidential" with sensitive info.        |
| 49  | `intitle:"index of" "top_secret"`                                            | Search for files or directories named "top_secret" with highly sensitive data.    |
| 50  | `intitle:"index of" "classified"`                                            | Search for files or directories named "classified" with classified information.  |
| 51  | `intitle:"index of" "parent directory"`                                     | Search for directories listing parent directories, potentially exposing data.   |
| 52  | `intitle:"index of" "directory listing"`                                    | Search for directory listings that may expose files and data.                   |
| 53  | `intitle:"index of" "public"`                                                | Search for files or directories named "public" that may contain public data.     |
| 54  | `intitle:"index of" "www"`                                                   | Search for directories typically associated with website root directories.      |
| 55  | `intitle:"index of" "files"`                                                 | Search for directories named "files" that may contain various types of data.    |
| 56  | `intitle:"index of" "data"`                                                  | Search for directories or files named "data" that may contain data sets or logs. |
| 57  | `intitle:"index of" "assets"`                                                | Search for directories named "assets" that may contain various resource files.   |
| 58  | `intitle:"index of" "public_html"`                                           | Search for directories typically used for serving web content publicly.          |
| 59  | `intitle:"index of" "wwwroot"`                                               | Search for directories typically used as web server root directories.            |
| 60  | `intitle:"index of" "uploads"`                                               | Search for directories named "uploads" that may contain user-uploaded files.     |
