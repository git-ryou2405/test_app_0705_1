source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.2'
gem 'rails-i18n'                # 日本語化
gem 'faker'                     # ダミーデータ自動生成用
gem 'bcrypt'                    # パスワード暗号化 "Use ActiveModel has_secure_password"

gem 'sqlite3'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'      # SCSS(Syntactically Awesome StyleSheet：効率的にCSSが書ける言語)
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootsnap', '>= 1.1.0', require: false

gem 'carrierwave'               # 画像のアップロード
gem 'bootstrap-sass'            # bootstrap導入
gem 'mini_racer'                # Javascriptの実行エンジンであるv8をRubyから叩ける用にしてくれるgem
gem 'hirb'                      # モデルの出力結果を表形式で表示するGem
gem 'hirb-unicode'              # 日本語などマルチバイト文字の出力時の出力結果のずれに対応

gem 'dotenv-rails'              # 環境変数を管理できるgem

gem 'devise'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-facebook'
gem 'omniauth-google-oauth2'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
