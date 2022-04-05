## B4P Installation



#### Linux - AMD64
```text
# wget file as 'raw' to avoid conversion to HTML
wget --no-check-certificate https://github.com/b4p-app/install-b4p/raw/main/b4p-linux-amd64.zip
unzip b4p-linux-amd64.zip 
sudo chmod -R 755 b4p-linux-amd64
cd b4p-linux-amd64
sudo ./setup --choice=machine --locale=en_US
```


#### Linux - ARM64
```text
# wget file as 'raw' to avoid conversion to HTML
wget --no-check-certificate https://github.com/b4p-app/install-b4p/raw/main/b4p-linux-arm64.zip
unzip b4p-linux-arm64.zip 
sudo chmod -R 755 b4p-linux-arm64
cd b4p-linux-arm64
sudo ./setup --choice=machine --locale=en_US
```


#### zip and unzip
```text
zip -r filename.zip foldername
unzip filename.zip
```
