require "rspec/core/rake_task"

desc "Run those specs"
  task :spec do
    RSpec::Core::RakeTask.new(:spec) do |t|
      t.rspec_opts = %w{--colour --format documentation}
    end
end