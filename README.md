# [Paper Dashboard PRO Angular](https://www.creative-tim.com/product/paper-dashboard-pro-angular) [![version][version-badge]][CHANGELOG]
 <!-- [![license][license-badge]][LICENSE] -->

![alt text](https://s3.amazonaws.com/creativetim_bucket/products/59/opt_pdp_angular_thumbnail.jpg "Paper Dashboard PRO Angular")

**[Paper Dashboard PRO Angular](https://www.creative-tim.com/product/paper-dashboard-pro-angular/)** is the premium version for the [Paper Dashboard Angular](https://www.creative-tim.com/product/paper-dashboard-angular), which is available for free download.


During the development of this dashboard, we have used many existing resources from awesome developers. We want to thank them for providing their tools open source:

* [Robert McIntosh](https://github.com/mouse0270) for the notification system
* [Chartist](https://gionkunz.github.io/chartist-js/) for the wonderful charts
* [Tristan Edwards](https://twitter.com/t4t5) for the [Sweet Alert](http://limonte.github.io/sweetalert2/)
* [Eonasdan](https://github.com/Eonasdan) for the [DateTimPicker](https://eonasdan.github.io/bootstrap-datetimepicker/)
* Kirill Lebedev for [jVector Maps](http://jvectormap.com/)
* [Vincent Gabriel](https://twitter.com/gabrielva) for the [Bootstrap Wizard](https://github.com/VinceG/twitter-bootstrap-wizard)
* [FullCalendar.io](https://fullcalendar.io/) for the awesome Calendar

 Let us know your thoughts below. And good luck with development!



## Links:

+ [Live Preview](https://www.creative-tim.com/product/paper-dashboard-pro-angular)
+ [Paper Kit - For Front End Development](http://www.creative-tim.com/product/paper-kit?ref=github-pd-pro-angular)

## Quick start

Quick start options:

- [Download from Creative Tim](http://www.creative-tim.com/product/paper-dashboard-pro-angular).

## Terminal Commands

1. Install NodeJs from [NodeJs Official Page](https://nodejs.org/en).
2. Open Terminal
3. Go to your file project
4. Run in terminal: ```npm install -g @angular/cli```
5. Then: ```npm install```
6. And: ```ng serve```
7. Navigate to: [http://localhost:4200/](http://localhost:4200/)

### What's included

Within the download you'll find the following directories and files:

```
pd-pro-angular
├── README.md
├── angular-cli.json
├── documentation
│   ├── css
│   │   └── documentation.css
│   └── elements.html
├── e2e
├── karma.conf.js
├── package.json
├── protractor.conf.js
├── src
│   ├── app
│   │   ├── app.component.css
│   │   ├── app.component.html
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── app.routing.ts
│   │   ├── calendar
│   │   │   ├── calendar.component.html
│   │   │   ├── calendar.component.ts
│   │   │   ├── calendar.module.ts
│   │   │   └── calendar.routing.ts
│   │   ├── charts
│   │   │   ├── charts.component.html
│   │   │   ├── charts.component.ts
│   │   │   ├── charts.module.ts
│   │   │   └── charts.routing.ts
│   │   ├── components
│   │   │   ├── buttons
│   │   │   │   ├── buttons.component.html
│   │   │   │   └── buttons.component.ts
│   │   │   ├── components.module.ts
│   │   │   ├── components.routing.ts
│   │   │   ├── grid
│   │   │   │   ├── grid.component.html
│   │   │   │   └── grid.component.ts
│   │   │   ├── icons
│   │   │   │   ├── icons.component.html
│   │   │   │   └── icons.component.ts
│   │   │   ├── notifications
│   │   │   │   ├── notifications.component.html
│   │   │   │   └── notifications.component.ts
│   │   │   ├── panels
│   │   │   │   ├── panels.component.html
│   │   │   │   └── panels.component.ts
│   │   │   ├── sweetalert
│   │   │   │   ├── sweetalert.component.html
│   │   │   │   └── sweetalert.component.ts
│   │   │   └── typography
│   │   │       ├── typography.component.html
│   │   │       └── typography.component.ts
│   │   ├── dashboard
│   │   │   ├── dashboard.module.ts
│   │   │   ├── dashboard.routing.ts
│   │   │   ├── overview
│   │   │   │   ├── overview.component.html
│   │   │   │   └── overview.component.ts
│   │   │   └── stats
│   │   │       ├── stats.component.html
│   │   │       └── stats.component.ts
│   │   ├── forms
│   │   │   ├── equal-validator.directive.ts
│   │   │   ├── extendedforms
│   │   │   │   ├── extendedforms.component.html
│   │   │   │   └── extendedforms.component.ts
│   │   │   ├── forms.module.ts
│   │   │   ├── forms.routing.ts
│   │   │   ├── regularforms
│   │   │   │   ├── regularforms.component.html
│   │   │   │   └── regularforms.component.ts
│   │   │   ├── validationforms
│   │   │   │   ├── password-validator.component.ts
│   │   │   │   ├── validationforms.component.html
│   │   │   │   └── validationforms.component.ts
│   │   │   └── wizard
│   │   │       ├── wizard.component.html
│   │   │       └── wizard.component.ts
│   │   ├── layouts
│   │   │   ├── admin
│   │   │   │   ├── admin-layout.component.html
│   │   │   │   └── admin-layout.component.ts
│   │   │   └── auth
│   │   │       ├── auth-layout.component.html
│   │   │       └── auth-layout.component.ts
│   │   ├── maps
│   │   │   ├── fullscreenmap
│   │   │   │   ├── fullscreenmap.component.html
│   │   │   │   └── fullscreenmap.component.ts
│   │   │   ├── googlemaps
│   │   │   │   ├── googlemaps.component.html
│   │   │   │   └── googlemaps.component.ts
│   │   │   ├── maps.module.ts
│   │   │   ├── maps.routing.ts
│   │   │   └── vectormaps
│   │   │       ├── vectormaps.component.html
│   │   │       └── vectormaps.component.ts
│   │   ├── pages
│   │   │   ├── lock
│   │   │   │   ├── lock.component.html
│   │   │   │   └── lock.component.ts
│   │   │   ├── login
│   │   │   │   ├── login.component.html
│   │   │   │   └── login.component.ts
│   │   │   ├── pages.module.ts
│   │   │   ├── pages.routing.ts
│   │   │   └── register
│   │   │       ├── register.component.html
│   │   │       └── register.component.ts
│   │   ├── shared
│   │   │   ├── fixedplugin
│   │   │   │   ├── fixedplugin.component.html
│   │   │   │   ├── fixedplugin.component.ts
│   │   │   │   └── fixedplugin.module.ts
│   │   │   ├── footer
│   │   │   │   ├── footer.component.html
│   │   │   │   ├── footer.component.ts
│   │   │   │   └── footer.module.ts
│   │   │   └── navbar
│   │   │       ├── navbar.component.html
│   │   │       ├── navbar.component.ts
│   │   │       └── navbar.module.ts
│   │   ├── sidebar
│   │   │   ├── sidebar.component.html
│   │   │   ├── sidebar.component.ts
│   │   │   └── sidebar.module.ts
│   │   ├── tables
│   │   │   ├── bootstraptable
│   │   │   │   ├── bootstrap.component.html
│   │   │   │   └── bootstrap.component.ts
│   │   │   ├── datatable.net
│   │   │   │   ├── datatable.component.html
│   │   │   │   └── datatable.component.ts
│   │   │   ├── extendedtable
│   │   │   │   ├── extendedtable.component.html
│   │   │   │   └── extendedtable.component.ts
│   │   │   ├── regulartable
│   │   │   │   ├── regulartable.component.html
│   │   │   │   └── regulartable.component.ts
│   │   │   ├── tables.module.ts
│   │   │   └── tables.routing.ts
│   │   ├── timeline
│   │   │   ├── timeline.component.html
│   │   │   ├── timeline.component.ts
│   │   │   ├── timeline.module.ts
│   │   │   └── timeline.routing.ts
│   │   └── userpage
│   │       ├── user.component.html
│   │       ├── user.component.ts
│   │       ├── user.module.ts
│   │       └── user.routing.ts
│   ├── assets
│   │   ├── css
│   │   ├── fonts
│   │   ├── img
│   │   ├── js
│   │   │   ├── jquery-jvectormap.js
│   │   │   ├── jquery.validate.min.js
│   │   │   ├── perfect-scrollbar.min.js
│   │   │   └── sweetalert2.js
│   │   └── sass
│   │       ├── paper
│   │       └── paper-dashboard.scss
│   ├── environments
│   │   ├── environment.prod.ts
│   │   └── environment.ts
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.css
│   ├── test.ts
│   ├── tsconfig.app.json
│   ├── tsconfig.spec.json
│   └── typings.d.ts
├── tsconfig.json
├── tslint.json
├── typings
└── typings.json

```

## Useful Links

More products from Creative Tim: <http://www.creative-tim.com/bootstrap-themes>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <http://www.creative-tim.com/products>

Affiliate Program (earn money): <http://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>

[CHANGELOG]: ./CHANGELOG.md

[LICENSE]: ./LICENSE

[version-badge]: https://img.shields.io/badge/version-1.0.1-blue.svg
