source 'http://rubygems.org'
group :development do
#  gem 'hpricot'
#  gem 'faker'
#  gem 'gimei'
  gem 'bullet' # N+1を検出時に画面にダイアログ表示
  gem 'brakeman' # `bundle exec brakeman` でセキュリティチェック実行  
  gem 'bundle-audit'# `bundle exec bundle-audit` でgemバージョンを調べてセキュリティ問題をチェック
  gem 'rack-mini-profiler'#リクエストの所要時間などをブラウザ画面に表示
end

group :test, :development do
  gem 'json'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rubocop'
  #gem 'rufo' #小さいrubocop
  gem 'rails-erd'
  #vagrant環境で開発する場合、config/environments/development.rbに以下を追加
  #BetterErrors::Middleware.allow_ip! "192.168.33.1"
  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'rspec', '~> 3.0'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'parallel_tests'
  gem 'jasmine'
  gem 'capybara'
  gem 'poltergeist'
  gem 'simplecov', require: false
  gem 'simplecov-rcov', require: false
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
end
end
