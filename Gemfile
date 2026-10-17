# frozen_string_literal: true

source "https://rubygems.org"

# Specify your gem's dependencies in jsonb_accessor.gemspec
gemspec

# Rails versions in the CI matrix require the JSON 2 API.
gem "json", "< 3"

local_gemfile = File.expand_path("Gemfile.local", __dir__)
eval_gemfile local_gemfile if File.exist?(local_gemfile)
