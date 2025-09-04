source "https://rubygems.org"

gem "google-cloud-discovery_engine-v1beta", "<= 0.20.1"
gem "govuk_app_config"

gem "prometheus-client"

group :test do
  gem "pry"
  gem "simplecov", require: false
end

group :development, :test do
  gem "brakeman", require: false
  gem "govuk_test"
  gem "rspec"
  gem "rubocop-govuk", require: false
end
