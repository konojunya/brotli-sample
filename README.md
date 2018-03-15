# brotli-sample

jquery-2.1.4.jsを圧縮する

## 使ったコマンド

```sh
$ wc -c <filename>
$ time ./brotli -q 9 jquery-2.1.4.js -o jquery.brotli // brotli用
$ time gzip -9 jquery-2.1.4.js
```


