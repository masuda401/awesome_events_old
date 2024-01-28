# AWESOME_EVENTS

## 6-2-4 Bootstrapの導入
```
nodebrew compile v15.14.0

nodebrew use v15.14.0

npm install -g yarn

bin/rails webpacker:install

bin/rails webpacker:compile
```

## 6-3-3 Githubアカウントでログインする機能の作成
```
EDITOR="code --wait" rails credentials:edit
```

## 7-3-2
```
bundle config set --local path vendor/bundle

bundle install
```

## 10
```
docker build --platform linux/amd64 -t myrailsapp .

DOCKER_BUILDKIT=1 docker build --platform linux/amd64 -t myrailsapp -f Dockerfile-buildkit .

docker run -i -t --platform linux/amd64 \
-v $(pwd):/app \
-v awesome_events_bundle:/app/vendor/bundle \
-v awesome_events_node_modules:/app/node_modules \
-p 3000:3000 \
awesome_events
```
CREATE DATABASE appdb CHARACTER SET = utf8mb4 COLLATE = utf8mb4_bin;
CREATE DATABASE appdb_test CHARACTER SET = utf8mb4 COLLATE = utf8mb4_bin;
GRANT ALL ON appdb.* TO app@'%' IDENTIFIED BY 'password';
GRANT ALL ON appdb_test.* TO app@'%';
RENAME USER 'root'@'localhost' to 'root'@'%';


qemu-x86_64: Could not open '/lib64/ld-linux-x86-64.so.2': No such file or directory
--->

node: error while loading shared libraries: libstdc++.so.6
--->

bin/rails s -b 0.0.0.0

bin/rails assets:precompile

