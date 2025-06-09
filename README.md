# gh-cicd-example

The goal of this project is to learn the notion of continuous integration and continuous deployment. A simple GitHub Actions workflow to deploy a static website to GitHub Pages

# details

Before starting to code I had to check the settings for this repository to activate github pages option, also I specified the build via github acctions
I have tested various workflows, I add comment to understand better what is happening.

- hello.yml: just a helloworld
- static.yml: takes the full content of the project and update it, so if there is a index.html file it will be shown like a normal website
- astro.yml: takes the content of the astro directory and upload it, this will substitute the static.yml deployment, if this completes later

# resources

<https://docs.github.com/en/actions>
<https://www.freecodecamp.org/news/learn-to-use-github-actions-step-by-step-guide/>
