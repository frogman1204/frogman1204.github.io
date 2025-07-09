source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins # GitHub Pages와 로컬 환경을 일치시킴

# gem "jekyll-theme-hamilton" # 이제 테마 파일을 직접 복사했으므로 이 줄은 주석 처리 또는 삭제

group :jekyll_plugins do
  # gem "jekyll-feed" # github-pages에 포함되어 있을 가능성이 높음
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]