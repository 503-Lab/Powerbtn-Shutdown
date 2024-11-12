# Powerbtn-Shutdown

Ubuntu で 電源ボタンが押されたら即時にシャットダウンする。

---

acpid が必要です。インストールしていない場合は、

```sh
sudo apt install acpid
```

で acpid を入れてください。

---

もし、うまく動作しない場合は `powerbtn.sh` に実行権限が付与されていない可能性があります。

```sh
sudo chmod +x /etc/acpi/powerbtn.sh
```
