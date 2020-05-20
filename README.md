# aws-lightsail

[Amazon Lightsail](https://aws.amazon.com/tw/lightsail/) 虛擬伺服器、儲存裝置、資料庫及網路的價格實惠、可預測。

[教程：在 Amazon Lightsail 中启动并配置 WordPress 实例](https://lightsail.aws.amazon.com/ls/docs/zh_cn/articles/amazon-lightsail-tutorial-launching-and-configuring-wordpress)

[教程：将 WordPress 网站连接到 Amazon Lightsail 中的 MySQL 托管数据库](https://lightsail.aws.amazon.com/ls/docs/zh_cn/articles/amazon-lightsail-connect-wordpress-to-mysql-managed-database)

[连接到 Amazon Lightsail 中的 MySQL 数据库](https://lightsail.aws.amazon.com/ls/docs/zh_cn/articles/amazon-lightsail-connecting-to-your-mysql-database)


## Note

[使用MySQL Workbench訪問Amazon Lightsail上的MySQL實例](https://stackoom.com/question/3vrqZ/%E4%BD%BF%E7%94%A8MySQL-Workbench%E8%AE%BF%E9%97%AEAmazon-Lightsail%E4%B8%8A%E7%9A%84MySQL%E5%AE%9E%E4%BE%8B)  
[使用 PuTTY 從 Windows 連線至您的 Linux 執行個體](https://docs.aws.amazon.com/zh_tw/AWSEC2/latest/UserGuide/putty.html)
使用 PuTTYgen 轉換私有金鑰

PuTTY 原本不支援 SSH 金鑰的私有金鑰格式 (.pem)。但 PuTTY 提供一套名為 PuTTYgen 的工具，可將金鑰轉換為 PuTTY 所需的格式。您必須先如下所示將您的私有金鑰 (.pem 檔案) 轉換為此格式 (.ppk 檔案)，才能使用 PuTTY 連線至您的執行個體。

[MySQL Workbench](https://dev.mysql.com/doc/workbench/en/)  
[Minimum Requirements for Windows](https://dev.mysql.com/doc/workbench/en/wb-installing-windows.html)  
[最新支援的 Visual C++ 下載](https://support.microsoft.com/zh-tw/help/2977003/the-latest-supported-visual-c-downloads)  

Microsoft Visual C++ Redistributable for Visual Studio 2019
[Visual Studio 2019 的可散發程式碼](https://docs.microsoft.com/zh-tw/visualstudio/releases/2019/redistribution)  

VISUAL C++ REDISTRIBUTABLE FOR VISUAL STUDIO 2019
https://www.sts-tutorial.com/download/credistributable2019


[Connect To PhpMyAdmin](https://docs.bitnami.com/aws/faq/get-started/access-phpmyadmin/)


[![Audi R8](http://img.youtube.com/vi/9VdcQLDmYII/0.jpg)](https://www.youtube.com/watch?v=9VdcQLDmYII "bitnami")  
PuTTY  
http://127.0.0.1:8888/phpmyadmin/

mysql > bitnami_wordpress

[WinSCP](https://winscp.net/eng/download.php)
/home/bitnami/ apps/wordpress/htdocs   

### MySQL Workbench

connect to Database
```
54.180.167.218:22
bitnami
LightsailDefaultKey-ap-northeast-2.pem
localhost
3306
bn_wordpress
bitnami_wordpress
```

`update wp_users set user_pass=MD5(RAND()) where id=2;`

## Tool

[Download PuTTY](https://www.putty.org/)
