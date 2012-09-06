source :rubygems

group :development, :test do
  # Generic
  gem "bundler"
  gem "rake"
  gem "json"

  # Deployment
  gem "git"
  gem "redcarpet" unless RUBY_PLATFORM =~ /java/
  gem "yard"

  # Testing
  gem "mocha"
  gem "shoulda"
  gem "test-unit", "2.5.0"
  gem "ci_reporter"
  gem "ruby-prof" unless RUBY_PLATFORM =~ /java/
  gem "rake-compiler"

  # Java
  platforms :jruby do
    gem "bouncy-castle-java"
    gem "jruby-launcher"
    gem "jruby-openssl"
    gem "posix-spawn" # XCode 4.4 - brew install apple-gcc42 && export CC=/usr/local/bin/gcc-4.2 && bundle install
  end
end
