source "https://rubygems.org"


group :development, :test do
  gem "rails"
  gem "sqlite3"
  gem "json_pure"
  gem "jeweler", git: 'git@github.com:technicalpickles/jeweler'
  # gem "jeweler", "~> 2.3"
  gem "rspec-rails"
  gem "rspec"
  gem "actionpack"
  gem "simplecov", :require => false
  gem "rake"

  gem 'nokogiri'

  gem "generator_spec"

  if RUBY_ENGINE == 'rbx'
    platforms :rbx do
      gem 'rubysl'
      gem 'rubysl-test-unit'
      gem 'psych', '~> 2.2'
      gem 'racc'
      gem 'rubinius-developer_tools'
    end
  end

end


# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19'
