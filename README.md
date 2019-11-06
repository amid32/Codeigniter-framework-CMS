# Codeigniter-framework-CMS
login: admin 
password: password


//==============================================================//
.htaccess kodu
-------------------------------
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule (.*) index.php/$1
