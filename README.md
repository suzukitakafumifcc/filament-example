# filament example

LaravelのUIフレームワーク、[filament](https://filamentphp.com/)の使用例です。

## （Laravel Sailでの）インストール

通常のLaravelアプリのクローン時と同様の操作を行ってください。
また、本リポジトリは[Laravel Sail](https://laravel.com/docs/11.x/sail)
を利用して開発しています。その他の環境の場合は、環境変数を変更してください。

### 環境変数の設定

```bash
cp .env.example .env
```

### Composer依存関係のインストール

```bash
docker run --rm \
    -u "$(id -u):$(id -g)" \
    -v "$(pwd):/var/www/html" \
    -w /var/www/html \
    laravelsail/php83-composer:latest \
    composer install --ignore-platform-reqs
```

### データベースのマイグレーション

```bash
sail artisan migrate
```

## 使用法

### ユーザーの作成

```bash
php artisan make:filament-user
```

`/admin`からログイン可能になります。

## プルリクエスト

Issue1を作成してください。

## License

[MIT](https://choosealicense.com/licenses/mit/)
