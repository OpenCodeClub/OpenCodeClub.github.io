# OpenCodeClub.github.io
## A great meetup where people can code together!

## We meet every Tuesday, from 6pm - 8.30pm.

### How To Create a Pull Request on GitHub

### Create a Copy of the Repository

In order to work on an open-source project, you will first need to make your own copy of the repository. To do this, you should fork the repository and then clone it so that you have a local working copy.

#### Fork the Repository

You can fork a repository on GitHub by navigating with your browser to the GitHub URL of the open-source project you would like to contribute to.
GitHub repository URLs will reference both the username associated with the owner of the repository, as well as the repository name. For example, DigitalOcean Community is the owner of the cloud_haiku project repository, so the GitHub URL for that project is:

**https://github.com/do-community/cloud_haiku**

In the above example, **do-community** is the username and **cloud_haiku** is the repository name.

Once you have identified the project you would like to contribute to, you can navigate to the URL, which will be formatted like so:

**https://github.com/username/repository**

Or you can search for the project using the GitHub search bar.

When you’re on the main page for the repository, you’ll see a “Fork” button on your upper right-hand side of the page, underneath your user icon:

Click on the fork button to start the forking process. Within your browser window, you’ll receive feedback that looks like this:

Once the process is done, your browser will go to a screen similar to the repository image above, except that at the top you will see your username before the repository name, and in the URL it will also say your username before the repository name.

So, in the example above, instead of **do-community / cloud_haiku** at the top of the page, you’ll see **your-username / cloud_haiku**, and the new URL will look like this:

**https://github.com/your-username/cloud_haiku**

With the repository forked, you’re ready to clone it so that you have a local working copy of the code base.

#### Clone the Repository

To make your own local copy of the repository you would like to contribute to, let’s first open up a terminal window.

We’ll use the **git clone** command along with the URL that points to your fork of the repository.

This URL will be similar to the URL above, except now it will end with **.git**. In the cloud_haiku example above, the URL will look like this:

**https://github.com/your-username/cloud_haiku.git**

You can alternatively copy the URL by using the green “Clone or download” button from your repository page that you just forked from the original repository page. Once you click the button, you’ll be able to copy the URL by clicking the binder button next to the URL:

Once we have the URL, we’re ready to clone the repository. To do this, we’ll combine the git clone command with the repository URL from the command line in a terminal window:

**$ git clone https://github.com/your-username/repository.git**

Now that we have a local copy of the code, we can move on to creating a new branch on which to work with the code.