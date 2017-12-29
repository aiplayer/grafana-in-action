# Grafana 配置
Grafana服务器提供一个配置文件，可以对服务器进行设置。该文件位于conf目录下。

该目录下缺省提供两个文件：
- 缺省配置文件：$WORKING_DIR/conf/defaults.ini
- 定制配置文件：$WORKING_DIR/conf/custom.ini
</br>注意：定制配置文件也可以通过启动命令参数进行覆盖，该参数为--config</br>

如果使用deb和rpm进行安装，则配置文件位于/etc/grafana/grafana.ini。这个路径信息在Grafana.ini.d中定义的。
<br>


