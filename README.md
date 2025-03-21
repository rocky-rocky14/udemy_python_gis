### コマンド
#### Docer起動
* `docker run --name gis-image -it --rm -v /Users/hiroki.ishizuka/git/udemy_python_gis:/workdir -p 8080:8080 561b9ae1a591`
* `cd workdir`
#### jupyter notebook起動
* `jupyter notebook --allow-root --no-browser --port=8080 --ip=0.0.0.0`