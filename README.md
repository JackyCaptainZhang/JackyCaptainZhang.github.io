## Initialization

1. Clone from template
2. Fork to your github and set the name as username.github.io and visibility public

## Install environment

3. brew install ruby node
4. echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
5. gem install bundler
6. bundle install

## Run the server

7. bundle exec jekyll serve --livereload --livereload-port 4004

## tutorial notes

- "\_data/authors" "\_data/navigation" "\_data/ui-text" stores some global variables and control the navigation bar.
- "\_pages" folder stores the page settings(main page(about.md),404 page) for each page item in navigation bar.
- "\_config.yml" is the global site settings (information and urls of author profile).
- Add files in folder "\_talk" "\_teaching" "\_posts" "\_portfolio" to upload markdown or HTML files to each item page in navigation bar.
- "footer.html" "social-share" and other files in "includes" folder is the controller for global component like foot bar and Blog and portfolio share function.
- "future:true/false" in "\_config.yml" controls the future post function.
- "\_includes/footer/custom.html" controls the sitemap function of the footer
