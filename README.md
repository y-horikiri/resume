# 堀切佑太郎の職務経歴書
内容は[こちら](https://y-horikiri.github.io/resume/)

## ローカル環境構築
GitHub Pagesに合わせて、RubyのJekyllライブラリでMarkdownを整形している。  
Pagesでの見え方をローカルで確認するにはRubyが必要。
   
```
# .ruby-versionに記載されたバージョンをrbenvでインストール
rbenv install "$(cat .ruby-version)"
rbenv rehash

# Gemをインストール
bundle install

# ローカルサーバーを起動
bundle exec jekyll serve --source docs
```

ブラウザで以下URLを開く  
http://localhost:4000
