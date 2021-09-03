# mysql-connector-python を使用して MySQL にアクセス
## add settings.json ( Code Runner )
```
    "code-runner.showRunIconInEditorTitleMenu": false,
    "code-runner.executorMapByFileExtension": {
        ".hta": "C:\\Windows\\SysWOW64\\mshta.exe",
        ".htm": "C:\\Windows\\SysWOW64\\mshta.exe"
    }
```

## python -m pip install mysql-connector-python

```python
cnn = mysql.connector.connect(
    host='localhost',
    port=3306,
    db='lightbox',
    user='root',
    passwd='',
    charset="utf8",
    autocommit='True')
```
