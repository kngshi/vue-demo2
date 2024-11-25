# Node.js の公式イメージをベースに使用
FROM node:18

# 作業ディレクトリを指定
WORKDIR /app

# 必要な依存関係をインストール
COPY package*.json ./
RUN npm install

# アプリのソースコードをコピー
COPY . .

# 開発サーバを実行（docker-compose.yml で指定）