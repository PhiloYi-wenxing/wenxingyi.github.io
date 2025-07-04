frozen_string_literal: true

source "https://rubygems.org"

# 使用GitHub Pages官方支持的版本
gem "github-pages", "~> 232", group: :jekyll_plugins

# 或者直接使用Jekyll（如果你想更精确控制版本）
# gem "jekyll", "~> 4.3"

# 主题依赖（如果你使用的是chirpy主题）
gem "jekyll-theme-chirpy", "~> 6.0", path: "."

# 测试工具
gem "html-proofer", "~> 5.0", group: :test

# Windows平台特定依赖
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
