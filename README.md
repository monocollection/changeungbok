# 장응복

- solo-exhibition
- group-exhibition
- collaboration
- workshop
- book

```shell
# lunar-sonata-2021
$ touch _project/group-exhibition/lunar-sonata-2021.md _project_en/group-exhibition/lunar-sonata-2021.md

$ mkdir img/group-exhibition/lunar-sonata-2021
$ find . -name "*.jpg" -exec bash -c 'file="{}"; npx @frostoven/squoosh-cli --mozjpeg auto --resize "{"enabled":true,"width":1500,"height":1500}" "$file"' \;
$ find . -name "*.jpg" -exec bash -c 'file="{}"; npx @frostoven/squoosh-cli --mozjpeg "{"quality":80}" "$file"' \;
```
