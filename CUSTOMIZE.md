# How to Customize the Template

## Homebrew Environment Setup

Run the following commands to set up a homebrew development environment.
```
homebrew install ruby
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc 
source ~/.zshrc

gem install bundler
bundle install
```

Run the following command to view the website on your local machine.
```
bundle exec jekyll serve -l -H localhost
```

## Configuration file (`_config.yml`)

- Site Author: Sets the information in the left side bar of the homepage.


## Navigation Bar (`_data/navigation.yml`)

Contains a list of navigation bar titles and their corresponding links. You can use links to pages or files in the GitHub repository or links to external websites.

## About / Main Page (`_pages/about.md`)