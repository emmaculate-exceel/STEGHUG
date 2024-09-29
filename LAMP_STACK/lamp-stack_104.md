# lamp stack implementation 104
### Installing mysql


##### mysql is a database management system(RDBMS) that uses structure Query language	for accessing and managing data
![Screenshot_2024-09-29_15_05_38](https://github.com/user-attachments/assets/9d329573-05d3-4fbe-9b71-1b1a803cf79c)

```
sudo apt install mysql-server
sudo mysql
```
![Screenshot_2024-09-29_15_08_43](https://github.com/user-attachments/assets/d8c05391-543a-4605-8d36-8c6b94e24099)



```
ALTER USER 'root'@'localhost' IDENTIFIED WITH 'mysql_native_password' BY 'PassWord.1';
exit
```
![Screenshot_2024-09-29_15_12_35](https://github.com/user-attachments/assets/00797786-5815-49d3-91ab-eba401e96e58)



#### securing mysql installation by improving mysql security

![Screenshot_2024-09-29_15_21_43](https://github.com/user-attachments/assets/459ff3ff-6e02-4ffb-9dcc-da17614fcee2)


```
sudo mysql_native_password
```
* follow the prompt and customize it to your taste