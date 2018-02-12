
# BuildingBloCS 2018 Website

## Development workflow

### Requirements

1. [Jekyll](https://jekyllrb.com/docs/installation/)
2. [Node.js](https://nodejs.org/)

### Setup

```
git clone -b mybranch --single-branch git@github.com:serverwentdown/buildingblocs.github.io.git
```

Install `grunt` tool:

```
npm install -g grunt
```

Install project dependencies:

```
npm install
```

### Building CSS from Sass

Start `grunt` and make it watch for `.scss` file changes:

```
grunt watch
```

### Serve the local website

```
jekyll serve
open http://localhost:4000
```

Visit the [Jekyll docs](https://jekyllrb.com/docs/) for more information on the [directory sturcture](https://jekyllrb.com/docs/structure/).

