source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in bullet_train-billing-usage.gemspec.
gemspec

git "https://github.com/tujucreative/bullet_train-core.git", branch: "main" do
  gem "bullet_train"
  gem "bullet_train-api"
end

gem "bullet_train-billing", github: "tujucreative/bullet_train-billing", branch: "main"

gem "sprockets-rails"

# Not a direct dependency of this repo; the starter provides it.
gem "active_hash"

gem "minitest-mock"

gem "standardrb", "~> 1.0"
