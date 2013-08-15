php-resque demo app


1.　インストール

Composerでインストール

composer.json

```
{
    "require": {
        "chrisboulton/php-resque": "1.2.x"
    }
}	
```



ハマりポイントメモ  
ジョブクラスを書き換えたら、Workerもリスタートしないとダメポ？
