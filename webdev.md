# Collection of tips, tricks & cool web apps for code studying

## SPAs with Preact, Svelte, Vue, Choo

- ★ RSS client, React/Redux: https://github.com/getstream/winds/, https://github.com/GetStream/Winds/blob/90d1b993e177ad613e828000f285a3900053c84d/app/src/components/Header.js
- Webtorrent Desktop: https://github.com/feross/webtorrent-desktop
- ★ Preact, PWA, IndexedDB, offline: https://github.com/trys/JournalBook
- ★ Svelte PWA, Mastodon client Pinafore: https://github.com/nolanlawson/pinafore/
- Nolan Lawson’s Pokedex: https://github.com/nolanlawson/pokedex.org/, 
http://www.pocketjavascript.com/blog/2015/11/23/introducing-pokedex-org
- Normal version, plus React-version, plus Angular-version: https://github.com/nosir/cleave.js/tree/master/src
- Simple Vue.js app: https://github.com/tholman/what-have-you-made-today/blob/master/src/components/siteTiles.vue
- Multiple reducers example: https://github.com/GetStream/Winds/blob/3efc4153984a21f29b4d9c5d29e39af24ed91b82/app/src/reducers.js
- Chrome extension (calls to the main API, use of i18n): https://github.com/pepelsbey/contenteditable/blob/master/background.js
- Brexit poll Slack bot: https://gist.github.com/ajfisher/2361c4fd200996a6a41272cad54b2fd0
- Simple reducers, lit-html: https://github.com/kahlil/kaf/blob/master/js/kaf-app.js
- Redux vs Context API: https://daveceddia.com/context-api-vs-redux/
- Svelte simple example: https://github.com/sw-yx/bettertwitter/tree/master/src
- Svelte webmentions (promise await, etc): https://www.swyx.io/writing/clientside-webmentions/

## Build tools

- NPM scripts: https://github.com/feross/studynotes/blob/master/package.json#L119-L137
- https://github.com/nolanlawson/pokedex.org/blob/master/bin/build.js
- Task automation with NPM run: http://substack.net/task_automation_with_npm_run
- Download fonts from Google Fonts to serve from your own website: https://google-webfonts-helper.herokuapp.com/fonts/open-sans?subsets=latin,cyrillic
- JSDoc with Typescript: https://medium.com/@trukrs/type-safe-javascript-with-jsdoc-7a2a63209b76, https://mobile.twitter.com/pfrazee/status/1084528851982663682

## JS Libs

- Safe JSON.parse, object to string: https://github.com/davidmarkclements/fast-safe-stringify
- Tiny event emitter: https://github.com/scottcorgan/tiny-emitter
- Nano id (like uuid): https://github.com/ai/nanoid
- How to work with money, Dinero.js: https://frontstuff.io/how-to-handle-monetary-values-in-javascript
- Create split view panes: http://nathancahill.github.io/Split.js/
- Smooth scrolling: http://callmecavs.com/jump.js/
- Lazy loading images: https://github.com/callmecavs/layzr.js
- Search, sort, filter: http://www.listjs.com
- Filtering soring: https://github.com/patrickkunka/mixitup
- Manipulate text by letters, words, sentences: http://julian.com/research/blast/
- Dates (like moment.js), nice code organization — small functions, tests: https://github.com/date-fns/date-fns/tree/master/src
- Multi range for `input type="range"` http://leaverou.github.io/multirange/
- Good parallax: https://github.com/GianlucaGuarini/parallax
- Format data in input (card number, phone number): http://nosir.github.io/cleave.js/
- Put dots with tooltips on images (like LabelMaker): https://codecanyon.net/item/visual-composer-addon-image-hotspot-with-tooltip/8729185
- CSS-only tooltips: https://github.com/kazzkiq/balloon.css :tada:
- CSS-only slider https://voltra.co/
- jQuery slider: http://jquery.malsup.com/cycle/
- Slider: http://kenwheeler.github.io/slick/
- Dragable drid JS, Packery: https://packery.metafizzy.co/; persistant order: http://codepen.io/desandro/pen/PZrXVv, https://github.com/metafizzy/packery/issues/337
- Trix modern WYSIWIG text editor from Basecamp: http://trix-editor.org
- Markdown editor with preview pane, scroll sync https://github.com/nhn/tui.editor
- Lunr: Javascript search: https://lunrjs.com/guides/getting_started.html
- Generate neat SVG graphs with JS: https://github.com/fnando/sparkline/blob/master/README.md
- Advanced locale [languages translations] support: https://projectfluent.org/

## JavaScript

- Bundlephobia, cost of modules: https://bundlephobia.com/
- funfunfunction short & fun videos (#gold):
  - Composition over Inheretance: https://www.youtube.com/watch?v=wfMtDGfHWpA
  - Factory functions in JavaScript: https://www.youtube.com/watch?v=ImwrezYhw4w
- Simple browser test with Selenium and Tape: https://gist.github.com/patrickarlt/931b129598703eed4dda
- Russian and English typograph: https://github.com/typograf/typograf
- Responsive tables: https://github.com/filamentgroup/tablesaw/blob/master/README.md
- JS Books: https://survivejs.com/, http://eloquentjavascript.net/
- Native lazy loading: https://www.andreaverlicchi.eu/native-lazy-loading-with-vanilla-lazyload/
- Build a game with vanilla JS: https://www.mullinstack.com/2020/02/22/build-arcade-game-vanilla-javascript-dom-manipulation/
- Encryption in the browser: https://blog.excalidraw.com/end-to-end-encryption/
- - JS Tips: https://github.com/loverajoel/jstips
- ★ JS snippets / solutions: https://htmldom.dev/strip-html-from-a-given-text/
- ★ https://github.com/ryanmcdermott/clean-code-javascript

### Svelte

- Compile Svelte in your head: https://lihautan.com/compile-svelte-in-your-head-part-1/

### Preact

- HTM's preact integration now includes hooks. 4.6kb for VDOM + JSX + hooks with no build step is good value-for-money, IMO: https://github.com/developit/htm, https://mobile.twitter.com/_developit/status/1220102334048624643

### React

- Render large lists efficiently with react-window: small library for virtualizing lists & grids. Renders what users can see vs all your items at once https://addyosmani.com/blog/react-window/
- React Native training: https://medium.com/react-native-training/position-element-at-the-bottom-of-the-screen-using-flexbox-in-react-native-a00b3790ca42
- File System in React: https://github.com/imshubhamsingh/file-system-react
- From Redux to Context: https://dev.to/csantiago132/how-to-migrate-from-redux-to-react-context-api-5gkc

## Node

- Fast web server: https://www.fastify.io/
- Create and Deploy a Node.js, Express, & PostgreSQL REST API to Heroku: https://www.taniarascia.com/node-express-postgresql-heroku/
- Simple (maybe too simple) auth with tokens: https://github.com/cakeinpanic/silly-node-auth/blob/master/app/routes.js

## Stock images, video

- ★ Free music: https://100.aaronparecki.com/
- Draw outline map of any city: https://anvaka.github.io/city-roads

## Cool docs

- Logux.io
- Redux: http://redux.js.org/docs/recipes/UsingObjectSpreadOperator.html
- https://docusaurus.io/

## HTML, CSS, Layout

- ★★★ Simple flexbox grid: https://www.taniarascia.com/easiest-flex-grid-ever/
- Solved By Flexbox, a few layout examples: https://philipwalton.github.io/solved-by-flexbox/
- ★★★ 1-line CSS snippets (Responsive, truncation, responsive media) https://justmarkup.com/log/2018/03/collection-of-css-snippets/
- CSS without SASS https://github.com/trys/trysv4/tree/master/src/css
- ★ Great little UI tips: https://twitter.com/i/moments/880688233641848832?s=13
- Shoelace component framework (with css variables) https://shoelace.style/
- Composable class names framework: http://tachyons.io
- Clever column usage in a blog post: http://book.glvrd.ru/indesign/
- Social meta tags generator: https://autonome.github.io/silobuster/
- Full viewport width images (hipsta) inside a fixed width container: https://css-tricks.com/full-width-containers-limited-width-parents/
- Google Fonts pairs: http://digitalsynopsis.com/design/best-google-font-combinations-typeface-pairings/
- making-password-managers-play-ball-with-your-login-form: https://hiddedevries.nl/en/blog/2018-01-13-making-password-managers-play-ball-with-your-login-form
- Animations Repaintless: http://szynszyliszys.github.io/repaintless/
- Easings in animation: https://easings.net/
- Styling native select in 2019: https://www.filamentgroup.com/lab/select-css.html
- Set current scroll position to `html` and then use it in CSS to show/hide/animate things: https://pqina.nl/blog/applying-styles-based-on-the-user-scroll-position-with-smart-css/
- Flexbox holy albatros: http://www.heydonworks.com/article/the-flexbox-holy-albatross
- Prevent accidental navigation when scrolling horizontally: https://dev.to/danburzo/css-micro-tip-prevent-history-navigation-on-horizontally-scrolling-elements-3iil
- Want to create responsive images fast? Try https://responsivebreakpoints.com
- Compress images in PRs https://calibreapp.com/blog/compress-images-in-prs
- ★ Modern CSS Reset: https://hankchizljaw.com/wrote/a-modern-css-reset/
- Making better custom select element: https://24ways.org/2019/making-a-better-custom-select-element/
- Common responsive layouts: https://hub.samsunginter.net/common-responsive-layouts-with-css-grid--and-some-without--/
- CSS color palette generator: https://yoksel.github.io/tema/
- Native Elements, styles for inputs, headers, buttons: https://native-elements.stackblitz.io/
- How to make iframe responsive: https://mobile.twitter.com/simevidas/status/1247295722699010057
- Create a user controlled dark or light mode: https://hankchizljaw.com/wrote/create-a-user-controlled-dark-or-light-mode/
- `<details>`: https://habr.com/en/post/477520/, https://daverupert.com/2019/12/why-details-is-not-an-accordion/
- quotations/citations/blockquotes: https://css-tricks.com/quoting-in-html-quotations-citations-and-blockquotes/
- A fun generator for CSS-only section separators: https://wweb.dev/resources/css-separator-generator
- Show specific img only in dark mode: https://mobile.twitter.com/flaviocopes/status/1254690503863525376
- Responsive images, srcset: https://cloudfour.com/thinks/responsive-images-the-simple-way/

## SVG

- ★★★ Free awesome svg icons: http://sergeychikin.ru/365/
- SVG animations: https://github.com/maxwellito/vivus
- SVG icons sprite usage live example: https://voltra.co/
- SVG flat company logos: http://konpa.github.io/devicon/
- ★ How to use SVG icons: https://fvsch.com/code/svg-icons/how-to/#section-adding
- SVG to clip path tool: https://yoksel.github.io/relative-clip-path/

## Colors

- Automatic UI Color Palette Generator: https://palx.jxnblk.com/
- Advanced palette generator: https://coolors.co
- Nice gradients in CSS: https://www.grabient.com/

## Polyfills

- `object-fit`, with video support: https://github.com/jonathantneal/fitie
- `object-fit`, better, but images only: https://github.com/bfred-it/object-fit-images
- Pretty select dropdown: http://code.octopuscreative.com/fancyselect/, https://select2.github.io/, https://github.com/filamentgroup/select-css (last one is just the select thing, not dropdown)
- IE11 Custom properties (`--myColor: red;`): https://github.com/nuxodin/ie11CustomProperties

## WordPress

- Advanced Custom Fields: custom fields, option pages, repeaters, very flexible: http://advancedcustomfields.com
- Types, for custom post types, custom taxonomies and custom fields: https://wordpress.org/plugins/types/screenshots/
- Shortcode manager: https://wordpress.org/plugins/shorty/
- Add typograph to Wordpress: http://dmitryshishkin.ru/all/tipograf-na-sayt/
- Duplicator for moving between hosts: https://wordpress.org/plugins/duplicator/
- EDD Yandex.Kassa plugin: https://sheensay.ru/edd-yandex-kassa

## Accessibility

- 7 things you need to know: https://medium.com/salesforce-ux/7-things-every-designer-needs-to-know-about-accessibility-64f105f0881b#.7nqvzajev
- https://medium.com/@matuzo/writing-css-with-accessibility-in-mind-8514a0007939
https://medium.com/alistapart/writing-html-with-accessibility-in-mind-a62026493412
- http://simplyaccessible.com/article/react-a11y/
- https://github.com/simplyaccessible/tv-db/blob/master/src/components/Announcements.js
- Automated Accessibility testing: https://github.com/pa11y/pa11y
- Simple Accessibility testing from Github: https://github.com/github/accessibilityjs
- https://inclusive-components.design/tabbed-interfaces/
- http://simplyaccessible.com/article/react-a11y/
- https://github.com/theKashey/react-focus-on — The final solution for WAI ARIA compatible modal dialogs or full-screen tasks.
- https://github.com/theKashey/aria-hidden — Hides from ARIA everything, except provided node. Helps to isolate modal dialogs and focused task - the content will be not accessible using accesible tools.
- Test level overview: http://qualitytesting.tech/test-level-overview/
- Accessibility checks: https://dequeuniversity.com/rules/axe/3.2
- 6 things to check for: https://www.matuzo.at/blog/beyond-automatic-accessibility-testing-6-things-i-check-on-every-website-i-build/
- 12 tips for more accessible react apps: https://www.matuzo.at/blog/12-tips-for-more-accessible-react-apps-slides-react-finland-2019/

## Nice Blog Layouts / Indie Web

- http://zaytsev.io/blog
- http://cherenkevich.com
- http://destroytoday.com
- https://aaronparecki.com/
- https://macwright.org
- http://manton.org
- https://eli.li/
- https://mmarfil.com/
- https://micro.blog

## Encrytption

- How to simply encrypt files on Mac and Linux: https://n-o-d-e.net/encrypt.html
- HTML page that generates an encrypted page: https://github.com/derhuerst/html-vault/blob/gh-pages/readme.md

## Misc

- Show recent Instagram posts on website: https://ifttt.com/applets/65778p-saves-your-instagrams-to-rows-in-a-google-drive-spreadsheet, jlord.us/blog
- Node on Android: https://github.com/node-on-mobile/node-on-android
- Lint forms: https://formlinter.com/
- Show JS errors on mobile: https://github.com/hcodes/show-js-error
- Minimum needed open graph sharing tags: http://www.phpied.com/minimum-viable-sharing-meta-tags/
- Alternatives to Google services, but also just a good list of services: https://nomoregoogle.com/
- Remove background from image (obtravit') automatically: https://www.remove.bg/
- Avatar generator: https://getavataaars.com/
- Landing rules: https://gist.github.com/ai/e3683b03ba936ade91d33dbc721cd6d8
