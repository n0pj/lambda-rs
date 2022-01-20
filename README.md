# nambda-rs

Lambda で Rust が使用できるテンプレート。Rust 1.57.0, Amazon Linux 2 対応。

## 使い方

### Setup Template

```
serverless install --url git@github.com:n0pj/nambda-rs.git --name nambda-fn && rm -rf nambda-fn/.git && cd nambda-fn
```

### 確認

```
serverless invoke -f lambda_rs -d '{"json":"test"}'
```

### デプロイ

```
serverless deploy
```
