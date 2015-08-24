# Munin-Raw-Value
MuninのRawValueを取得できますわよ。

## How to USE  

1.Install smartctl  
2.Install this plugin  
3.Edit /etc/munin/plugin-conf.d/munin-node  
4.Setting

#### 2.Install this plugin
1.Download this plugin  
2.sudo mv /your_download_directory/smart_raw_value_ /usr/share/munin/plugins/smart_raw_value_  
3.sudo chmod 755 /usr/share/munin/plugins/smart_raw_value_  
4.sudo ln -s /usr/share/munin/plugins/smart_raw_value_ /etc/munin/plugins/smart_raw_value_[device]

[device example]  
/dev/sda is  
sudo ln -s /usr/share/munin/plugins/smart_raw_value_ /etc/munin/plugins/smart_raw_value_sda    
/dev/sdb is  
sudo ln -s /usr/share/munin/plugins/smart_raw_value_ /etc/munin/plugins/smart_raw_value_sdb

#### 4.Setting
Add to /etc/munin/plugin-conf.d/munin-node

[smart_raw_value_*]  
user root  

# Finally  
1.Free all(Public Domain)  
2.Not support  
3.You are ok?  
4.Let's Go!!  
