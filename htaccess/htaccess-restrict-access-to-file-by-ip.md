# Htaccess restrict access to file by ip

General example

```shell script
<Files full-path-to-the-file>
    order deny,allow
    Deny from all
    Allow from ip_address
</Files>
```

Wordpress login example

```shell script
<Files wp-login.php>
    order deny,allow
    Deny from all
    Allow from 111.111.111.111
</Files>
```