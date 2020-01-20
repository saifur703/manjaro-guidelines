### Open Apache & MySQL
```
sudo /opt/lampp/lampp start
```

### Open Xampp Visual Mode
```
cd /opt/lampp
cd ./manager-linux-x64.run
```

### Go to htdocs Folder
```
cd /opt/lampp/htdocs
```

#### For installing WordPress, create a folder in htdocs but before, change the permission of htdocs
```
1. Go to lampp folder by "cd /opt/lampp
2. Type => chmod a+rwx htdocs
```

### As usual go and take a cofee.
```
https://localhost/phpmyadmin
Download WordPress file and Paste it into the Directory you created in htdocs
Install it by https://localhost/directoryname
```

### Change permission of wp-content
```
cd /opt/lampp/htdocs/directoryname
chmod a+rwx wp-content
```

### Change permission of WordPress plugins folder
```
chmod a+rwx plugins
```
### Create a Folder named "uploads" into wp-content directory and change the permission
```
chmod a+rwx uploads
```

###### If need any permission others directory, you have to do as like above methods. Have a Good Journey!!!
