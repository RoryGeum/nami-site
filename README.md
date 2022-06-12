[![Netlify Status](https://api.netlify.com/api/v1/badges/5702ba89-7242-490e-b04d-e4a691faced5/deploy-status)](https://app.netlify.com/sites/fernfolio/deploys)

# Fernfolio
The super simple portfolio template built with [Eleventy](https://www.11ty.io/) and [Netlify CMS](https://www.netlifycms.org/)

<img width="1280" alt="fernfolio screenshot" src="https://raw.githubusercontent.com/TylerMRoderick/fernfolio-11ty-template/master/fernfolio-preview.png">

### <pre>🖥  [Demo](https://fernfolio.netlify.app/)</pre>

## 🤔 What is this?
An [Eleventy](https://www.11ty.io/) theme designed to simplify the process of deploying a beautiful portfolio and blog. Launch your site in minutes!

Based on the [eleventy-netlify-boilerplate](https://github.com/danurbanowicz/eleventy-netlify-boilerplate), but modified to perfectly fit the needs of a modern technical porfolio.

## ✨ Features
* Built in support for [Netlify CMS](https://www.netlifycms.org/) with editor previews
* Customizable blog and project pages with tag support
* Working contact form powered by [Netlify Forms](https://www.netlify.com/products/forms/)
* Super fast page render and high lighthouse scores
* Uses Markdown for content files and Nunjucks for layouts
* 100% Javascript framework free
* Continuous Deployment workflow via [Netlify](https://www.netlify.com/)
* Base styles powered by [Sakura](https://github.com/oxalorg/sakura) classless css framework
* Vanilla css for custom styles (keep it simple)




## 💻 Development Scripts

**`npm start`**

> Run 11ty with hot reload at localhost:8080

**`npm run build`**

> Generate minified production build

Use this as the "Publish command" if needed by hosting such as Netlify.

Checkout the Eleventy [Command Line Usage docs](https://www.11ty.dev/docs/usage/) for more options 


## 🎩 Common issues

If you change the repo that was created at deploy time from public to private, you'll need to regenerate your token,
as the token generated using the deploy to Netlify button can only access public repositories. To
regenerate your token, head to "Settings" in your Netlify site dashboard, go to the "Identity"
section, then scroll to "Services" where you'll see an "Edit settings" button. Click that and you'll
see a text link to "Generate access token in GitHub".
