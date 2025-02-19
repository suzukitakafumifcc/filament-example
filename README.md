# Filament Example

Laravelの管理画面パッケージ[Filament](https://filamentphp.com/)の開発例です。

## インストール

### 環境変数の設定

```bash
cp .env.example .env
```

### Composerパッケージのインストール

```bash
composer install
```

### アプリケーションキーの生成

```bash
php artisan key:generate
```

### データベースのマイグレーション

```bash
php artisan migrate
```

## 使い方

### Filamentユーザーの作成

```bash
php artisan make:filament-user
```

### 開発サーバーの起動

```bash
composer run dev
```

## Contributing

プルリクエストは歓迎します。大きな変更については、まずIssueを開いて変更したい内容について話し合ってください。

必要に応じてテストを更新してください。

## License

[MIT](https://choosealicense.com/licenses/mit/)
