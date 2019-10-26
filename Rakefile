# cf. How to test a Jekyll site
# http://joenyland.me/blog/how_to_test_a_jekyll_site/

require 'html-proofer'
task test: [:build] do
  options = {
    allow_hash_href:  true,
    check_opengraph:  true,
    check_favicon:    true,
    check_html:       true,
    disable_external: true,
    # NOTE: You can ignore files or URLs as follows
    #file_ignore: [
    #  /node_modules/,
    #  "./_site/PATH_TO_IGNORE_FILE
    #],
    #url_ignore:  %w(coderdojo.com linkedin.com),
    #http_status_ignore: [0, 500, 999],
  }

  HTMLProofer.check_directory('./_site', options).run
end

task build: [:clean] do
  system 'bundle exec jekyll build'
end

task :clean do
  system 'bundle exec jekyll clean'
end
