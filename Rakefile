require 'html/proofer'

task :test do
  sh "bundle exec jekyll build -c _config.yml,_config_test.yml"
  HTML::Proofer.new("./_site", :check_html => true, :check_favicon => true).run
end
