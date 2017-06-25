# apache2-ensite
Here is the apache2 ensite configuration. There are comments on the each line. You can follow the guide to setup the configuration. There are two files. One is 000-default.conf. Two is default-ssl.conf. The one is for automatically guiding to HTTPS from HTTP. The two is for HTTPS. In addition, you must enable SSL module. (i.e. How to enable it is "sudo a2enmod ssl" this command line.) 

There are four elements you must have.
1. ServerName, this is your web address such as www.google.com. (The google.com is the web server's alias)
2. The web server's physical location on your machine such as normally /var/www/your_folder or /usr/share/your_folder.
3. The log file's folder where is on /var/log/${APACHE_LOG_DIR}/your_log_folder.
4. The SSL certificate, a HTTPS server mush require this certificate. The linux built-in SSL, snakeoil, is alreadly written on this profile. (i.e. You don't need to prepare one except you want a none built-in SSL.)

If you have any questions, please kindly email to jeff7037@gmail.com
