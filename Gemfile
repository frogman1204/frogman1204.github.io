# frozen_string_literal: true

source "https://rubygems.org"

# GitHub Pages에서 Jekyll 사이트를 빌드하기 위한 모든 종속성을 포함합니다.
# 이 젬은 jekyll 젬을 포함하므로, 아래에 별도로 gem "jekyll"을 명시할 필요 없습니다.
gem "github-pages", group: :jekyll_plugins

# 사용하고 싶은 Jekyll 테마 젬을 명시합니다.
gem "jekyll-theme-hamilton"

# Jekyll-Feed와 같은 추가 플러그인을 사용하려면 여기에 추가합니다 (github-pages 젬에 포함되지 않은 경우).
group :jekyll_plugins do
  # gem "jekyll-feed" # github-pages에 이미 포함되어 있을 가능성이 높으므로 주석 처리
end

# Windows 환경에서 일부 젬의 작동을 위해 필요합니다.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows에서 파일 변경 감지 성능 향상을 위한 젬입니다.
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby 환경을 위한 특정 젬 고정.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]