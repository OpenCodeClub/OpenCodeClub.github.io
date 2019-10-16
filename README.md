# OpenCodeClub.github.io

Website for Open Code - [click for live version](https://opencodeclub.github.io/)

Put together as part of an introduction to using GitHub and pull requests by students of codebar Birmingham!

## A great meetup where people can code together!

## We meet every Tuesday, from 6pm - 8.30pm.

### How To Contribute to This Project

### Create a Copy of the Repository

In order to work on this open-source project, you will first need to make your own copy of the repository. To do this, you should fork the repository and then clone it so that you have a local working copy.

#### Fork the Repository

You should see a “Fork” button on the upper right-hand side of the page, underneath your user icon.

Click on the fork button to start the forking process. Within your browser window, you’ll receive feedback that looks like this:

Once the process is done, your browser will go to a screen similar to the repository image above, except that at the top you will see your username before the repository name, and in the URL it will also say your username before the repository name.

So, in the example above, instead of **OpenCodeClub / OpenCodeClub.github.io** at the top of the page, you’ll see
**your-username / OpenCodeClub.github.io**, and the new URL will look like this:

**https://github.com/your-username/OpenCodeClub.github.io**

With the repository forked, you’re ready to clone it so that you have a local working copy of the code base.

#### Activate the Pages Site

This project is using [GitHub Pages](https://help.github.com/en/articles/about-github-pages) to host the website.

To activate your version of the site, so that you can see what effect any changes you make have, click on Settings under your repository name. 

Scroll down to the "GitHub Pages" section, use the Source drop-down menu and select "master branch" as your publishing source.

The settings will update, and tell you the URL that your version of the site will appear at. It will probably be:

**https://your-username.github.io/OpenCodeClub.github.io**

(If you already have a GitHub User Page with a custom domain set up, the URL will be different. The settings panel will tell you where it is. If "GitHub User Page with a custom domain set up" means nothing to you, don't worry, you can ignore this part!)

#### Clone the Repository

To make your own local copy of the repository, let’s first open up a terminal window.

We’ll use the **git clone** command along with the URL that points to your fork of the repository.

This URL will be similar to the URL above, except now it will end with **.git**:

**https://github.com/your-username/OpenCodeClub.github.io.git**

You can alternatively copy the URL by using the green “Clone or download” button from your repository page. Once you click the button, you’ll be able to copy the URL by clicking the binder button next to the URL:

Once we have the URL, we’re ready to clone the repository. To do this, we’ll combine the git clone command with the repository URL from the command line in a terminal window:

**$ git clone https://github.com/your-username/OpenCodeClub.github.io.git**

Now that we have a local copy of the code, we can move on to creating a new branch on which to work with the code.

#### Install Jekyll
##### Install Ruby
###### Mac
```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install ruby
gem install --user-install bundler jekyll
```
###### Linux (ubuntu)
```
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
```
######  Windows
- Download Ruby+Devkit from https://rubyinstaller.org/downloads/
- Follow the install setup and make sure you run the ridk install
- Open comand prompt from the start menu
- Install Jekyll with `gem install jekyll bundler`

#### Run Jekyll
```
jekyll serve
```
Go to localhost:4000 in your browser.