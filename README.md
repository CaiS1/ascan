# Ascan

Ascan 可以轻松帮你解决API接口众多时的烦恼

## Install

```
▶ go intsall github.com/0zard/ascan@latest
```

## Basic Usage

从stdin或者文件中读取

```
▶ cat domains.txt
a.com
s.com
s.cn
▶ cat domains.txt | ascan
http://a.com GET 200 ok HTML <title>xxxx</title>
https://s.com POST 200 ok JSON {axx:aaa,a:xxx}
▶./ascan -l domains.txt
```
## Help

```
  -c int
        set the concurrency level (default 20)
  -l string
        filename location
  -t int
        timeout (milliseconds) (default 10000)
  -v    output errors to stderr
```
## 推荐

```
https://github.com/tomnomnom/httprobe
https://github.com/tomnomnom
https://github.com/Qianlitp/crawlergo
https://github.com/Threezh1/JSFinder
```
