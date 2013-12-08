golangota
=========
1.使用Apple企业账号创建Ad-Hoc证书和in-house mobileprofile.

2.archive app程序。选择distribute。确保选择的证书是企业账号证书。输入applicationURL为：http://自己IP地址:8080/xxx.ipa。导出pilist和ipa文件。把这两个文件放到golangota文件目录下面;

3.在index.html中<a href=.....&url=http://自己ip地址:8080/xxx.plist>;

4.在终端中输入go run golangota.go;

5.手机使用safari浏览器输入自己ip地址：8080/index.点击install app


使用golang搭建简单的webserver。部署ios企业ipa
