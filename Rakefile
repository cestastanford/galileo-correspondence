# Galileo 
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
  system "jekyll serve --watch --config _config.yml,_config-dev.yml"
end
