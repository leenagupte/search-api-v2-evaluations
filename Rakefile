require "rake"
require "rspec/core/rake_task"

Dir.glob("tasks/*.rake").each { |r| load r }

RSpec::Core::RakeTask.new(:spec)

desc "Lint Ruby"
task :lint do
  sh "bundle exec rubocop"
end

task default: %i[spec lint]
