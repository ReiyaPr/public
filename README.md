
# Memo
Memoはローカルホスト上で動くメモアプリです！ 

# 特徴
直感的に使えるシンプルなメモアプリ  
配色は2色のみでスッキリ！

# 必要なライブラリ
* ruby 3.0.0
* bundler 2.2.3 
* sinatra-contrib (2.1.0)
* sinatra (2.1.0)
* webrick (1.7.0)
 
# ライブラリのインストール
- ディレクトリの準備  
mkdir memo_apps  
cd memo_apps  
bundler init  
bundlerはruby 2.6以降は `gem install bundler`無しで使用可能  

- GemFileに下記の内容を記述  
gem 'sinatra'  
gem 'webrick'  
gem 'sinatra-contrib'  

- 一括インストール  
bundle install --path vendor/bundle 

# 使い方
cd memo_apps  
git clone `https://github.com/ReiyaPr/Public`  
bundle exec ruby memo.rb  
`http://localhost:4567/にアクセス`  
```
 
