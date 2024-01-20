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
```