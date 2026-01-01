# Rishi's Personal Website

This is the code for my website: https://rishibommasani.github.io/.  
If you find errors on my website or would like to reuse it for your own purposes, contact me at rishibommasani@gmail.com.

## Local preview

Run the site locally (without pushing) using the GitHub Pages Jekyll stack:

1. Use the Homebrew Ruby we installed: `export PATH="/opt/homebrew/opt/ruby@3.1/bin:$PATH"`
2. Install dependencies: `bundle install`
3. Serve locally: `bundle exec jekyll serve --port 4001`
   - Visit http://127.0.0.1:4001
   - Stop the server with `pkill -f jekyll` or by killing the printed PID.
4. Build without serving: `bundle exec jekyll build` (output goes to `_site/`, which is gitignored).
