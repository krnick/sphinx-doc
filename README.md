# sphinx-doc


## install step

```bash
pip3 install sphinx
```


## 主題設定
安裝python官方模板主題

```bash
pip3 install sphinx_rtd_theme
```

修改設定文檔

```bash
$ vim conf.py
```

```
html_theme = 'sphinx_rtd_theme'
```



開始使用

將寫好的.rst 檔案 放入資料夾

執行

```bash
make html
```

即可產生網頁
