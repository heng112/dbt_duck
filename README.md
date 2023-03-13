# dbt_duck

DuckDBを利用したdbt環境

### 環境構築

- インストール

```
curl -OL https://github.com/duckdb/duckdb/releases/download/v0.6.1/duckdb_cli-osx-universal.zip
unzip duckdb_cli-osx-universal.zip
```
https://duckdb.org/docs/installation/index


### duckDB 動作コマンド

- 起動
```
./duckdb [DB名].db
```

- 終了
```
.exit
```