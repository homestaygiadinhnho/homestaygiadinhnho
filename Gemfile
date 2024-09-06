source "https://rubygems.org"

# Khai báo phiên bản Ruby cụ thể
ruby "2.7.4" # Thay thế 2.7.4 bằng phiên bản Ruby của bạn

# Khai báo các gem cần thiết cho dự án
gem "rails", "~> 6.1.4"
gem "jekyll", "~> 4.2.0"
gem "nokogiri", "~> 1.11.1"

# Khai báo các gem cho Jekyll plugins
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-paginate'
  gem 'jekyll-seo-tag'
end

# Nếu bạn sử dụng Windows, thêm gem 'wdm'
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
