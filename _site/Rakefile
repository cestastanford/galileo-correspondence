# Stanford Digital History
# Modified from Jason A. Heppler:
# http://github.com/hepplerj/jekyll-blog/Rakefile

desc "nuke and rebuild"
task :nuke do
    sh 'rm -rf _site'
    system "jekyll"
end

desc "watch the site and regenerate when it changes"
task :watch do
  puts "Starting to watch source with Jekyll."
  system "jekyll serve --watch"
end

desc "preview site in browser with localhost:4000"
task :preview do
  puts "Starting site preview in http://localhost:4000."
  system "jekyll serve"
end
