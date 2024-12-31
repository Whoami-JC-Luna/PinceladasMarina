# pinceladasmarina
### SO: Fedora40 

Clonar el reposotiorio del theme: 

**Make sure you've ruby, bundler and jekyll in your local machine

Clone the repository form https://github.com/StaticMania/roxo-jekyll

Install dependency using command bundle install --> Check the installed versions and adjust the Gemfile and Gemfile.lock to resolve issues with the gems versions.

Serve locally by using bundler exec jekyll serve command -->   In my case, I had to manually install gems that weren’t being installed with the current versions when running bundle install due to version conflicts. For example, the rexml gem required by kramdown and the webrick gem. Afterward, I added the webrick gem to the Gemfile and ran bundle install again, which increased the number of installed gems. From there, I proceeded by executing bundler exec jekyll serve, and everything worked as expected. 

Build your site by using command jekyll build. 



