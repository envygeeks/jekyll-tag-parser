# Frozen-string-literal: true
# Copyright: 2017 - 2020 - ISC License
# Author: Jordon Bedwell
# Encoding: utf-8

# --
# 🔖
# RSpec, MiniTest, Whatever.
# --
task default: [:spec]
task :spec do
  exec 'script/test'
end
# --
# 🔖
# RSpec, MiniTest, Whatever.
# --
task :test do
  exec 'script/test'
end
# --
# 🔖
# @see .rubocop.yml
# Rubocop.
# --
task :rubocop do
  exec 'script/lint'
end
# --
# 🔖
# @see .rubocop.yml
# Rubocop.
# --
task :lint do
  exec 'script/lint'
end

# --
Dir.glob('script/rake.d/*.rake').each do |v|
  load v
end
