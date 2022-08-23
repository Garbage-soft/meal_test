# こんなエラー出た時

```
#11 0.384 Composer could not find a composer.json file in /var/www/html/laravel                                                                            
#11 0.384 To initialize a project, please create a composer.json file. See https://getcomposer.org/basic-usage                                             
------
executor failed running [/bin/sh -c composer install]: exit code: 1
ERROR: Service 'php' failed to build : Build failed
```

こちら実行してみてください
`docker-compose run php composer install`