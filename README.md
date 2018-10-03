# bye-Earth
征程史记所对应的实际内容，由 Pico CMS（http://picocms.org/）驱动

以docker方式运行：
docker run --name cms-bye-earth -d -v `pwd`/html:/var/www/html/content-sample -v `pwd`/images.conf:/etc/httpd/conf.d/images.conf -v `pwd`/images:/var/www/img -p 6789:80 techyugadi/picocms


$ docker cp pico.php cms-bye-earth:/var/www/html/lib/.
docker stop cms-bye-earth
docker start cms-bye-earth

安装之后测试：
http://localhost:6789/JAXA-Hayabusa2-sample-return

## Syntax ref

https://daringfireball.net/projects/markdown/syntax
