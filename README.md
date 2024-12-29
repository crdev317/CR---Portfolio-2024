# crdev317.github.io

#https://crdev317.github.io/crdev317-crdev317.github.io/#home

GitHub Pages Create a Repository There are two different types of GitHub Pages repositories:

User sites are hosted at https://YOUR_USERNAME.github.io and are used for things like personal homepages, portfolio pages, and other sites associated with you as a user. To create a user site GitHub Pages repository, create a repo named YOUR_USERNAME.github.io.

Project sites are hosted at https://YOUR_USERNAME.github.io/YOUR_REPO_NAME and are used for documentation related to a specific repo, or standalone pages. To create a project site GitHub Pages repository, create a repo with any name, and then either:

Create a branch in that repo named gh-pages. Go to the Settings tab of your repo and enable GitHub Pages for the main branch (or any branch you want). (There’s a third type of GitHub Pages repository called an organization site, but you probably don’t need that right now.)

For now, create a user site GitHub Pages repository by creating a repo named YOUR_USERNAME.github.io. When you create your repo, check the Add a README file box.

Click the Create repository button to create your repo!

Confirm Your GitHub Pages Settings Next, go to the Settings tab of your repo and scroll down to the GitHub Pages section. Creating a repo named YOUR_USERNAME.github.io automatically activates the GitHub Pages feature and enables these settings. If you wanted to turn a different repo into a GitHub Pages site, this is where you’d do that!

But if you’re working from a YOUR_USERNAME.github.io repo, you don’t have to change any settings. Go back to your repo’s homepage (the Code tab).

Test Your URL Right now, your GitHub Pages site is hosted at https://YOUR_USERNAME.github.io, but your repo only contains a single README.md file. To test that everything is working, point your browser to https://YOUR_USERNAME.github.io/README.md. You should see something like this: This is the raw content of the README.md file, hosted on GitHub Pages. Unlike the GitHub profile README feature, GitHub Pages does not convert markdown into HTML by default, which is why you see the raw markdown in your browser.

Add an HTML File Next, follow the flow you learned in the GitHub profile README tutorial to add an index.html file to your repo.

Clone your repo. You can use GitHub Desktop or the git command line tool.

Create an index.html file containing some HTML content and save it to the local copy of your repo. You can use any text editor to do this step.

Here’s some HTML content to start with:

<title>My GitHub Pages Site</title>
Hello world!
Welcome to my GitHub Pages site!

Save this to your index.html file in your repo, right next to your README.md file. You can test your HTML by opening the file in your browser.
Add, commit, and push your index.html file. Again, you can use either GitHub Desktop or the git command line tool. Go back to your repo in GitHub, and you should now have an index.html file in your repo.

View Your HTML File Now here’s the magic part! Point your browser to https://YOUR_USERNAME.github.io/index.html and you’ll see your HTML rendered by the browser. The index.html file is also a bit magical. By default, most web servers will automatically show index.html if you don’t specify a file. That means you can also navigate to https://YOUR_USERNAME.github.io without the index.html part to see your page!

https://happycoding.io/tutorials/html/github-pages#:~:text=View%20Your%20HTML%20File,-Now%20here's%20the&text=the%20magic%20part!-,Point%20your%20browser%20to%20https%3A%2F%2FYOUR_USERNAME.github.io%2F,is%20also%20a%20bit%20magical.
