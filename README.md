# genpasswd_simple

セキュアなパスワードジェネレーター（シンプル版）。
サービスごとの履歴管理が必要な場合は [genpasswd](https://github.com/takeweb/genpasswd) を使用してください。

## 環境構築
```
cargo add clap --features derive
cargo add rand
cargo add rand_distr
```

## コマンドのインストール　＊注意: crates.ioに同名のコマンドが存在する為。
```
cargo install --path .
```

## 使い方
```

genpasswd_simple -h
Secure Password Generator

Usage: genpasswd_simple [OPTIONS]

Options:
  -l, --length <LENGTH>  Length of the password [default: 16]
  -s, --symbols          Include symbols in the password
  -h, --help             Print help
  -V, --version          Print version
```

以上
