# MyGemfile
my develop Gemfile

#解説
hpricot
faker
gimei
## bullet
N+1を検出時に画面にダイアログ表示
## brakeman
`bundle exec brakeman` でセキュリティチェック実行  
## bundle-audit
`bundle exec bundle-audit` でgemバージョンを調べてセキュリティ問題をチェック
## rack-mini-profiler
リクエストの所要時間などをブラウザ画面に表示
json
pry-byebug
pry-rails
rubocop
## rufo
小さいrubocop
`rufo {filepath}`
Rails.root/.rufoのルールに従いフォーマットを整理する
### 参考
https://qiita.com/totto357/items/31552e899b737b529244#align_assignments
## better_errors,binding_of_caller
エラー画面でデバックできる様にする
vagrant環境で開発する場合、config/environments/development.rbに以下を追加
BetterErrors::Middleware.allow_ip! "192.168.33.1"

##rails-erd
ERDを生成する
`bundle exec erd`


rspec, ~> 3.0
rspec-rails
factory_girl_rails
parallel_tests
jasmine
capybara
poltergeist
simplecov, require: false
simplecov-rcov, require: false
end

group :assets do
sass-rails
coffee-rails
end
