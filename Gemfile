source 'https://rubygems.org'

# Specify gem dependencies in active_model_serializers.gemspec
gemspec

rails_version = ENV["RAILS_VERSION"] || "default"

rails = case rails_version
when "master"
  {github: "rails/rails"}
when "default"
  ">= 3.1.0"
else
  "~> #{rails_version}"
end

gem "rails", rails
