# pomera-o24




```
# hwdbファイルを作成
sudo nano /etc/udev/hwdb.d/90-onishi-layout.hwdb

# 上記の内容を貼り付けて保存後、適用
sudo systemd-hwdb update
sudo udevadm trigger

```
