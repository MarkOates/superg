task make: %w[build update]

task :build do
  `gem build superg.gemspec`
end

task :update do
  `gem install ./superg-0.0.1.gem`
end
