# nextjs-ts-jest-express-docker-templete

# 環境

Docker + TypeScript + Next + Express + jest

インストールしたいものがある場合(Dockerfileに書いても良い)

```
$ docker-compose run --rm nextjs yarn add <追加したいライブラリなど>
```

コンテナ立ち上げ

```
$ docker-compose up
```

立ち上がったら `http://localhost:3000` にアクセス