# ONU Mujeres - Paz y seguridad web

This website was developed by Rodolfo Miranda Company ( [la bau—la](https://www.labaula.net/) ) for [United Nations Women LATAM](https://www.bsc.es/). 
*	Development start date: 20/10/2020
*	Development end date: ongoing
*	[Template preview](https://www.labaula.net/terrenodepruebas/jicara/)

### Development environment setup
Development environment is using node.js, npm package installs and gulp as task manager. 
You can see dependencies inside `package.json` file.
For running dev environment open terminal and enter command `gulp`.
*	Main JS file is `/src/scripts/main.js`
*	Main SCSS file is `/src/scss/main.scss`

### Development snapshot

#### Front-end
*   For html templeting we are using [Nunjucks](https://mozilla.github.io/nunjucks/templating.html)
*	For styling, the project is using [SASS](https://sass-lang.com/) 
*	For front end code JavaScript is being used along with [jQuery](https://jquery.com/) and [GSAP](https://greensock.com/)
*	All icons were customly crated using IcomoonSVG [Icomoon](icomoon.io/)
*	To see console logs please set `App.console : true` in main.js file
*	To see page wire set `$wire-size: 0px;` in `/src/scss/_utils.scss` file

#### Back-end


### Deployment
Follow the steps below to distribute the app:
*	From termianl run gulp task `dist`
*	For deployment please copy files from `/dist` folder to the server



### DOM Layout

#### Sections
Below you can see the main DOM structure for our website's sections. You can replace `<section></section>` tag for whatever html tag you want, for example `<header></header>`. Main page sections should live inside `<main></main>` tag.

```html
<section>
    <div class="main-wrap main-padding">
        <div class="main-container">
            <div class="your-content">
                ... your content goes here
            </div>
        </div>
    </div>
</section>
```

#### Template breakpoints

*	@media (max-width: 1200px)
*	@media (max-width: 992px)
*	@media (max-width: 792px)



### Other info




