# mysql-connector-python を使用して MySQL にアクセス

python -m pip install mysql-connector-python

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
