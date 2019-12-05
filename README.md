# Microsoft based Infographic Template
This is a starter template for a typical Indigo Slate infographic with Microsoft as the client.  This template includes fonts, icons and typical specifications pertaining to Microsoft projects.

## Environment
* [npm](https://www.npmjs.com/features?gclid=Cj0KCQiAi7XQBRDnARIsANeLIeu5j3pDVzQq5zmYrhf-OP5XJoSLq0BjIBVsAWnGXVQOYBMPRu1yZCcaAoj1EALw_wcB)
* [SASS](https://github.com/sass/sass)
    * Includes [Bootstrap Grid](https://getbootstrap.com/docs/4.0/layout/grid/) as a scss partial
* [Gulp](https://gulpjs.com/)
* [jQuery](https://jquery.com/)
* [Greensock](https://greensock.com/)

## Development
```bash
$ npm install
```
Then run:

```bash
$ gulp start
```

## Deployment via GitHub Pages

This template is optimized for deployment via GitHub pages.  This is optimal for setting up a quick and easy staging site.

This is done by building the project into a sub-folder called **docs** (instead of "build" or "dist" or whatever naming convention you usually use to build your project into.)

In order to set up this deployment via GitHub Pages you can do the following:
  1. Go to the **Settings** tab within the specific GitHub repo
  2. Navigate dowm to the **GitHub Pages** section
  3. Under **Source** select the **master branch / docs folder** option
  4. This will then deploy the build from the **docs** folder within the master branch whenever you commit to master
  5. You can view your deployed site at https://indigoslate.github.io/ **_name-of-your-repo_**
