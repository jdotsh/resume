# Resume

## Features

- Write resume in Markdown
- Basic pagination of your resume

## Getting Started

### Prerequisites

- [NodeJS](https://nodejs.org/) OR [yarn](https://yarnpkg.com/lang/en/docs/install/)
- Basic knowledge of navigating the terminal

### Installation

> If your plan is follow the tutorial all the way through to deployment, make sure you fork this project instead of simply cloning it!

In your terminal, navigate to the desired directory where you want this project to live.

```bash
# Clone the repo for local development
git clone https://github.com/jdotsh/resume.git

# Change directory into project
cd resume

# Install dependencies
npm i # OR yarn

# Run local server
npm run dev docs # OR vuepress dev docs
```
You should now be able to visit [http://localhost:8080](http://localhost:8080)!

## Build

```bash
# Build static files to .vuepress/dist
npm run build docs OR vuepress build docs
```

## Deploy with Netlify

Import your site in Netlify

1. Create a new site in Netlify and import your repository.
2. Set the build command to: `npm run build docs`
3. Set the publish directory to `docs/.vuepress/dist`

That's it, now your site gets deployed automatically on `git push`

### Style Override

Modify .vuepress/styles/palette.styl file

```css
/* font */
$fontSize = 13px
$fontWeight = 400

/* colors */
$accentColor = #4688F1
$textColor = #161F28
$borderColor = #eaecef
```

## Documentation

To check out the tutorial and docs, check out [the guide]().


## Examples

- [Demo:](https://www.sherollari.it/)

For more details, please head VuePress's [documentation](https://v1.vuepress.vuejs.org/).

## License

- [MIT](http://opensource.org/licenses/MIT) Copyright (c) 2020 - Present, Julian Sherollari
