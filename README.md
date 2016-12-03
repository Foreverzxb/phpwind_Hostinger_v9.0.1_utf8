# phpwind_Hostinger_v9.0.1_utf8
 为Hostinger主机空间优化的版本，只优化数据库读写错误问题，其它未改动
 文件 /src/applications/install/controller/IndexController.php 
 $result = $pdo->query("SHOW DATABASES")->fetchAll();
 修改为 
 $result = array();
