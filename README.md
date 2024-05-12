## Set ups

### Initialization

1. Clone from template(https://github.com/academicpages/academicpages.github.io)
2. Fork to your github and set the name as username.github.io and visibility public

### Install environment

3. brew install ruby node
4. echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
5. gem install bundler
6. bundle install

### Run the server

7. bundle exec jekyll serve --livereload --livereload-port 4004 (any port you like)

## tutorial

### Website Settings

- `authors.yml` `navigation.yml` `ui-text.yml` in `_data` folder store global variables and control the navigation bar.
- `_config.yml` is the global site settings (information and urls of author profile).
- `footer.html` `social-share` and other files in `_includes` folder is the controller for global component like foot bar and Blog and portfolio share function.
- `future:true/false` in `_config.yml` controls the future post function for blog and portfolio.
- `_includes/footer/custom.html` controls the sitemap icon of the footer.

### File uploading and content update

- Add files in folder `_talk` `_teaching` `_posts` `_portfolio` to upload markdown or HTML files to each item page in navigation bar.
- **!!File name of the file must start with the date as shown in example files!!**
- To update about main page, go to `_pages/mainPage.md`.
- To update about me page (cv), go to `_pages/aboutMe.md`.
- To update contact me information, go to `_pages/contactMe.md`.
- To update 404 information, go to `_pages/404.md`.
