## 1. Executing Multiple Commands
To run multiple commands sequentially in a single line, use the semicolon (`;`).
```
cd new_file; mkdir asia; pwd
```
---

## 2. Flags like -p to avoid file do not exists error
> Long Way
```
mkdir /tmp/asia
mkdir /tmp/asia/india
mkdir /tmp/asia/india/hyd
```
> Efficient_way
```
mkdir -p /temp/asis/india/hyd
```
---
## 3. `-o` for curl command to download the contents into a file 
```
curl https://site.com/file -o
wget https://site.com/file -o some-file-name.txt
```
---
## 4. To check OS- releases
> `*release*` includes astrik as a wildcard becoz its formats will be differnet for each distro ,So,it is better to use wildcard
```
cat /etc/*release*
```
---
## 5. 
