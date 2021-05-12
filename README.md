# Astronomy Club IITK Website

This is the official repo for the homepage of Astronomy Club IIT Kanpur, going to the moon :rocket:. 

`NOTE`: Currently as it is under development phase during the SnT tenure 2022-23, if you visit the homepage, make sure to `hard reload` the site using **Ctrl+Shift+R** to see any changes. It will soon be completed and the same shall be notified.

## Installation
You may want to run the website locally, probably to deep dive into the code, find any bug/issue or contribute to improve the website. The site is served using Jekyll, a Ruby-based static site generator with immense support for Github pages. You may need to go through the [installation process](https://jekyllrb.com/docs/installation/) for the Jekyll depending on your OS. For Ubuntu, the steps are also written here for ease:
- Install Ruby and other prerequisites:
```bash
sudo apt-get install ruby-full build-essential zlib1g-dev 
``` 
- Avoid installing RubyGems packages (called gems) as the root user. Instead, set up a gem installation directory for your user account. The following commands will add environment variables to your ~/.bashrc file (or say ~/.zshrc, depending on your shell) to configure the gem installation path:
```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```
- Finally, install Jekyll and Bundler:
```bash
gem install jekyll bundler
```

Now all set, you are ready to clone and start serving the site locally.
- Clone the repo and move into it
```bash
git clone https://github.com/gurbaaz27/astroclubiitk.git
cd astroclubiitk
```
- Install the dependecies
```bash
bundle install
```
- Serve the site and head over to <localhost:4000>
```
bundle exec jekyll serve --livereload --baseurl ''
```

## Contributers
| Name | Work Domain |
|---|---|
| [Gurbaaz Singh Nandra](http://github.com/gurbaaz27) | Programming |
| [Varun Muralidharan](https://github.com/Varun2501) | UI/UX |
| Mohammad Saad | Content Writing |
| Sunny Kumar Bhagat  | Content Compilation |
| Varun Singh | Content Compilation |

We always welcome an issue or suggestion! Also feel free to contribute via PR. If deemed worthy, we would more than happy to incorporate it :smile:.

## Credits
A big shoutout to [Dean Attali](https://deanattali.com), who developed the [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll) theme  :heart:. Do check out his account and repositories to explore other cool stuff!
