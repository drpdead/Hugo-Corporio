<h1 align="center">
  (Ambiguous) Hugo-Corporio
</h1>

<h3 align="center">
  Corporation Website Template - Ready for Content
</h3>

<p align="center">
  Corporio is an enterprise level corporation website template leveraging latest technologies making it secure, fast, and SEO-ready — by default - 
</p>

This version has been edited for ambiguity, especially in variables. It is ready for content, and differs, somewhat superficially, from the original version by [Amin Zibayi](https://github.com/AminZibayi/Corporio)

<!-- <p align="center">
  <a href="https://github.com/AminZibayi/Corporio/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/AminZibayi/Corporio?style=flat-square" alt="GitHub">
  </a>
  <a href="https://github.com/AminZibayi/Corporio/releases">
    <img src="https://img.shields.io/github/v/release/AminZibayi/Corporio?include_prereleases&style=flat-square"alt="GitHub release (latest SemVer including pre-releases)">
  </a>
  <a href="https://www.npmjs.com/package/@hyas/core">
    <img src="https://img.shields.io/npm/v/@hyas/core?style=flat-square" alt="npm (scoped)">
  </a>
  <a href="https://github.com/AminZibayi/Corporio/actions?query=workflow%3A%22Hyas+CI%22">
    <img src="https://img.shields.io/github/workflow/status/AminZibayi/Corporio/Hyas%20CI/master?style=flat-square" alt="GitHub Workflow Status (branch)">
  </a>
  <a href="https://app.netlify.com/sites/hyas/deploys">
    <img src="https://img.shields.io/netlify/895a161c-86be-48a2-8c57-a8c5d68cd1a4?style=flat-square" alt="Netlify">
  </a>
</p> -->

![Corporio — Corporation Website Template](https://raw.githubusercontent.com/drpdead/Hugo-Corporio/main/images/tn.png)

- [Why Corporio?](#why-corporio)
- [Requirements](#requirements)
- [Get Started](#get-started)
  - [Standalone Website](#standalone-website)
    - [1. Create a new site](#1-create-a-new-site)
    - [2. Install dependencies](#2-install-dependencies)
    - [3. Start development server](#3-start-development-server)
- [Tina CMS](#tina-cms)
  - [Using TinaCMS development mode](#using-tinacms-development-mode)
  - [Using TinaCMS with Corporio in production](#using-tinacms-with-corporio-in-production)
  - [Building without TinaCMS](#building-without-tinacms)
  - [Benefits of using TinaCMS](#benefits-of-using-tinacms)
- [Other commands](#other-commands)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Communities](#communities)
- [License](#license)

## Why Corporio?

Eight reasons why you should use Corporio:

1. **Security aware**. Get A+ scores on [Mozilla Observatory](https://observatory.mozilla.org/analyze/corporio.onrender.com) out of the box. Easily change the default Security Headers to suit your needs.
2. **Fast by default**. Leveraging the fastest static site generator, delivering optimized and minified static assets on the fastest CDNs on Render and Netlify.
3. **SEO-ready**. Use sensible defaults for structured data, open graph, and Twitter cards. Or easily change the SEO settings to your liking.
4. **Tina Integrated**. Do you prefer a graphical user interface over a text editor? or do you want to deliver the website to your non-technical customer? If so, Corporio is already integrated with tina, a feature-rich headless CMS.
5. **Development tools**. Code with confidence. Check styles, scripts, and markdown for errors and fix automatically or manually.
6. **Responsive**. Build robust, flexible, and intuitive websites with that looks best on any device.
7. **Integrated Blog**. Beside the modern and well-designed company landing page, Corporio ships with a built-in and ready full-featured blog.
8. **Products Page**. Introduce your products and services perfectly and impress your customers with our stunning product pages.
9. **Deploy-ready**. Deploy to Netlify or Render with sensible defaults. Easily use Netlify Functions, Render Redirects, and Headers.

## Requirements

- [Node.js](https://nodejs.org/) — latest LTS version

## Get Started

Start a new Corporio themed site in two ways either as a theme or as a standalone website
Please note that it is recommended to use PNPM however you may also use NPM or Yarn, but they are not guaranteed to work.

### Standalone Website

#### 1. Create a new site

```bash
git clone https://github.com/drpdead/Hugo-Corporio.git hugo-site && cd hugo-site
```

#### 2. Install dependencies

```bash
npm install
# OR
pnpm install
```

#### 3. Start development server

```bash
npm run start
# OR
pnpm start
```

## Tina CMS

The Corporio template includes integration with TinaCMS, an open-source headless content management system. TinaCMS allows you to edit and manage content directly within GitHub repositories using a graphical editing interface.

### Using TinaCMS development mode

The `tina:dev` script starts TinaCMS in dev mode along with the Hugo development
server. This allows editing content in TinaCMS and seeing changes live.
Head to http://localhost:1313/admin to see Tina admin panel.
Be sure to take a look at the tina configuration file(s) at `tina/config.js` to 
ensure there are no edits or additions that need to be made before building. Variables and templating
is done through tina and my schema, or the original schema, may not work for you particular use case. 

### Using TinaCMS with Corporio in production

The `tina:build` script builds TinaCMS alongside generating a static site output with Hugo.

- Sign up for a free Tina account at https://tina.io/
- Create a new project and connect your GitHub repository that contains the Corporio codebase
- Enter your own tina clientId and token in `tina/config.js`
- Tina will automatically detect the configuration for collections and fields in tina/config.js
- You can then edit content in Tina's sidebar interface or modal popups
- Saved changes will commit back to your connected repo

### Building without TinaCMS

If you don’t need Tina integration, you can use the command `pnpm build`. This command will skip the Tina build step.

### Benefits of using TinaCMS

- Edit content visually without needing to edit code
- Integrated workflow using your existing Git repo
- Collaborate with other editors and content creators
- Work with both markdown and YAML content
- Flexible fields and media management

## Contributing

## ALL CONTRIBUTIONS SHOULD BE MADE TO THE ORIGINAL DEVELOPER OF THE CORPORIO THEME AT ITS GITHUB REPO 
## [Corporio by Amin Zibayi](https://github.com/AminZibayi/Corporio)

with all attention paid to any systems in place with which to do so. 

-OR-
You can contribute to this project by using it to create your own website, sharing it with your friends, sharing your ideas or reporting a bug through opening an issue and informing us if you have crafted your website using Corporio.
Contribution to the source code and documentation are highly welcome, there are many comments in the source code containing the keyword `TODO:` which could be a good staring point for you, feel free to ask a question by opening an issue.

## License

[The MIT License](https://github.com/AminZibayi/Corporio/blob/master/LICENSE)
