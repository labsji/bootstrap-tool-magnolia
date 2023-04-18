# Magnolia Light Module Content Bootstrap Utility - a simple content app that helps bootstrap content in light modules. 

[Content bootstrap tool]

## Features
[A simple app that helps content boostrap via the tasks app.
During magnolia light development or while inducting a light module, you might want to bootstrap content associated with the module manually.
While, Jcr-tools app is the most appropriate for the job, if you wish content import be done in a (manual) workflow, then Bootstrap-tool is better suited for content import.

Bootstrap-tool app simply creates a content-import task taking the absolute filesystem path of the content file to be imported along with the workspace where the content is destained.

You can open the Tasks app, assign the content import task to the appropriate role/user. And effect the actual content import.

]


## Usage
[Install the bootstrap-tool-magnolia module from cli:
mgnl install bootstrap-tool-magnolia

This installs a content Bootstrap-tool App.
The Bootstrap-tool takes a file (Absolute) path and a repository name and creates a Content Import Manual Task.
Open the Tasks App and complete the Import.

Hint: Open the Bootstrap-tool app, enter the absolute file system path of content file  to be bootstrapped.

]


## Information on Magnolia CMS
This directory is a Magnolia 'light module'.

https://docs.magnolia-cms.com

Search the docs for `sharing light modules` for details on how to share and use light modules on npm and github.


## Contribute to the Magnolia component ecosystem
It's easy to create components for Magnolia and share them on github and npm. I invite you to do so and join the community. Let's stop wasting time by developing the same thing again and again, rather let's help each other out by sharing our work and create a rich library of components.

Just add `magnolia-light-module` as a keyword to npm's package.json to make them easy to find and use on npm.

## License

MIT

## Contributors

Magnolia, https://magnolia-cms.com

Balaji Sowmyanarayanan: labsji
