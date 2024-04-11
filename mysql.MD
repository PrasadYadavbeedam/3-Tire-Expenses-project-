Mysql database server instalation 

step 1
  we have to insatll sql >>>>>   dnf install mysql-server -y
  Start sql application   >>>    systemctl enable mysqld
                                 systemctl start mysqld
step 2 
   We need to change the default root password in order to start using the database service  >>>>>   mysql_secure_installation --set-root-pass ExpenseApp@1

                                   
