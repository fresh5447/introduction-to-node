## Introduction To Node

Learn node in this linear code along. It explores HTTP, express, params, posting  data, and rendering a static page.

----

## Resources
[Command Line Notes](https://github.com/fresh5447/introduction-to-node/blob/master/CL.md)

[Node Powerpoint](https://docs.google.com/presentation/d/1RgeLtO8DaSwroeRqQK1M25Y_w7dByuC-HG9Y8akRJoc/edit)

----


### Up and Running

#### Create Local Code Base

Create a project locally, titled `node_introduction`, and make a file `README.md`. In this file add some text `# Hello World!`

`mkdir node_introduction`
`cd node_introduction`
`touch README.md`
`atom .`
Add text to `README.md`

#### Create Github repository and sync  your project.

Head to Github.com and create a new repository titled node_introduction. Copy the URL to your clipboard, this is your `remote`, think of it as a bridge that ties your local code base to your GH repo.

Back in command line
`git init` // initialize git in the project
`git add -A` // stage your commit
`git commit -m "My first commit"` // give your commit a MSG
`git remote add origin <GH_URL_FOR_REPO>` // tie your local and remote together
`git push -u origin master` // pushes your code up to GITHUB

#### One more time with GIT

That was a unique workflow we do whenever we create a new project. Keeping our project up to speed over time is much easier. Likes practice by updating our `README.md`

Head to your `README.md` and make some changes. Then we will push these changes up to GH.

`git status` // see what has changed
`git add -A` // stage your commit
`git commit -m "Update Readme"` // name your commit
`git push origin master` // push up to github
