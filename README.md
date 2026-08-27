<div align="center">
	<img width="500" height="350" src="media/awesome-rshiny-logo.svg" alt="Awesome">

</div>

[![Join the chat at https://gitter.im/awesome-rshiny/Lobby](https://badges.gitter.im/awesome-rshiny/Lobby.svg)](https://gitter.im/awesome-rshiny/Lobby?utm_source=badge\&utm_medium=badge\&utm_campaign=pr-badge\&utm_content=badge)  [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources for R Shiny.  (*Featured on [Awesome-R](https://awesome-r.com/)*)

# Awesome rshiny with stars

* [Resources](#resources)
* [General](#general)
* [Community](#community)
* [Deployment](#deployment)
* [Tutorials](#tutorials)
* [Tools](#tools)
* [Packages](#packages)
* [Integrations](#integrations)
* [People](#people)
* [Books](#books)
* [Galleries](#galleries)
* [App Examples](#app-examples)
* [Contributors](#contributors)

## Resources

### General

* [GitHub](https://github.com/rstudio/shiny) ⭐ 5,682 | 🐛 866 | 🌐 R | 📅 2026-08-26
* [Official Website](http://shiny.rstudio.com/)
  * [Blog](https://blog.rstudio.org/category/shiny/)
  * [Articles](http://shiny.rstudio.com/articles/)
  * [Old Webinars Page](https://www.rstudio.com/resources/webinars/)
    * [Shiny Essentials](https://www.rstudio.com/resources/webinars/#shinyessentials)
    * [Advanced Shiny](https://www.rstudio.com/resources/webinars/#advancedshiny)
  * [New Webinars Page](https://resources.rstudio.com/webinars)
  * [2019/2020 Conference](https://www.rstudio.com/conference/)
  * [Training](https://www.rstudio.com/certified-partners/)
  * [Consultants](https://community.rstudio.com/groups/consultants/)
  * [Function References](http://shiny.rstudio.com/reference/shiny/latest/)

### Community

* [Shiny Server Forum](https://support.rstudio.com/hc/en-us/sections/204025308-Shiny-Server)
* [Stack Overflow Questions](http://stackoverflow.com/questions/tagged/shiny)
* [R-bloggers](http://www.r-bloggers.com/search/shiny)
* [Google Group](https://groups.google.com/forum/#!forum/shiny-discuss)
* [RStudio Community](https://community.rstudio.com/c/shiny)
* [rOpenSci](https://ropensci.org/)
* [R-Shiny on Reddit](https://www.reddit.com/r/rshiny/)
* [RGov - Government network for R/Shiny](https://rdotgov.wordpress.com/deploy-shiny/)

### Deployment

#### Self Hosting

* [Shiny Server](https://github.com/rstudio/shiny-server) ⭐ 759 | 🐛 204 | 🌐 JavaScript | 📅 2026-04-14 - Back end software that builds a web server for shiny apps.
* [ShinyStudio](https://github.com/dm3ll3n/ShinyStudio) ⭐ 241 | 🐛 8 | 🌐 Shell | 📅 2020-07-17 - Builds on the [Rocker project](https://www.rocker-project.org/) by including ShinyProxy to provide secured access to RStudio, VS Code, and Shiny.
* [RStudio Connect](https://www.rstudio.com/products/connect/) - Back end software for hosing shiny applications, Rmarkdown, plus other features for enterprise contexts.
* [Shinyproxy](https://www.shinyproxy.io/) - Uses containers for hosting shiny apps and a Java server control and proxy traffic to the app containers. [How-to Blog](http://lukesingham.com/shiny-containers-with-shinyproxy/).

#### Platform As A Service (PAAS)

* [Heroku](https://www.heroku.com) - General cloud application platform that can be utilised by shiny apps with these [buildpack scripts](https://github.com/virtualstaticvoid/heroku-buildpack-r/tree/heroku-16) ⭐ 305 | 🐛 4 | 🌐 R | 📅 2025-05-08.
* [ShinyApps.io](http://www.shinyapps.io/) - Rstudio's PAAS specifically for hosting shiny apps.

### Tutorials

* [The R-Podcast](https://r-podcast.org/)
  * [Episode 15: Introduction to Shiny](https://r-podcast.org/episode/015-introduction-to-shiny/)
  * [Episode 16: Interview with Dean Attali](https://r-podcast.org/episode/016-interview-with-dean-attali/)
  * [Episode 17: A simply Radiant Chat with Vincent Nijs](https://r-podcast.org/episode/017-a-simply-radiant-chat-with-vincent-nijs/)
  * [Episode 18: Interviews with the R-Studio Team](https://r-podcast.org/episode/018-interviews-with-the-rstudio-team/)
  * [Episode 19: Talking Shiny at R-Studio Conf wiht Barabara Borges and Dean Attali](https://r-podcast.org/episode/019-talking-shiny-at-rstudio-conf-with-barbara-borges-and-dean-attali/)
  * [Episode 21: Talking Rcpp and More with Dirk Eddelbuettel](https://r-podcast.org/episode/021-talking-rcpp-and-more-with-dirk-eddelbuettel/)
  * [Episode 25: Interview with Ian Lyttle (Rstudio::Conf 2018](https://r-podcast.org/episode/025-rstudioconf-ian-lyttle/)
  * [Episode 27: Get The {Gt} Tables (Rstudio::Conf 2019)](https://r-podcast.org/episode/027-rstudioconf-tables/)
* [R-Studio (video)](https://shiny.rstudio.com/tutorial/)
  * [RStartHere](https://github.com/rstudio/RStartHere) ⭐ 661 | 🐛 6 | 🌐 R | 📅 2019-09-16
  * [Effective Reactive Programming – Part 1 & Part 2](https://www.rstudio.com/resources/videos/effective-reactive-programming/)
  * [Coordinated multiple views (linked brushing)](https://www.rstudio.com/resources/videos/coordinated-multiple-views-linked-brushing/)
  * [Building interactive tools for exploratory data analysis (gadgets)](https://www.rstudio.com/resources/videos/building-interactive-tools-for-exploratory-data-analysis/)
  * [Improvements in deploying apps](https://www.rstudio.com/resources/videos/deploying-apps/)
  * [Modularizing Shiny app code](https://www.rstudio.com/resources/videos/modularizing-shiny-app-code/)
  * [Shiny UI](https://www.rstudio.com/resources/videos/shiny-ui/)
  * [Debugging Techniques](https://www.rstudio.com/resources/videos/debugging-techniques/)
  * [Profiling and Performance](https://www.rstudio.com/resources/videos/profiling-and-performance/)
  * [Interfacing DataTables](https://www.rstudio.com/resources/videos/interfacing-datatables/)
  * [Complex application layouts with Grid Style Sheets](https://www.rstudio.com/resources/videos/grid-style-sheets/)
  * [Building Dashboards](https://www.rstudio.com/resources/videos/building-dashboards/)
* [R-Studio (YouTube)](https://www.youtube.com/playlist?list=PL9HYL-VRX0oTAHdR62i2YaLNmJhFiiwaO)
* [R-Studio (Vimeo)](https://vimeo.com/rstudioinc)
* [DataCamp](https://www.datacamp.com/)
  * [Building Web Applications in R with Shiny](https://www.datacamp.com/courses/building-web-applications-in-r-with-shiny)
  * [Dean Attali: Shiny Case Studies: My new online interactive video course (DataCamp)](https://deanattali.com/blog/shiny-use-cases-datacamp-course/)
* [Dean Attali](https://deanattali.com/shiny/)
  * [Advanced-Shiny](https://github.com/daattali/advanced-shiny) ⭐ 1,215 | 🐛 1 | 🌐 R | 📅 2025-12-21
  * [CRANalerts: Get email alerts when a CRAN package gets updated](https://cranalerts.com/)
  * [Blog Post:  Building Shiny apps - an interactive tutorial](http://deanattali.com/blog/building-shiny-apps-tutorial/)
  * [Blog Post:  Shiny tips & tricks for improving your apps and solving common problems](http://deanattali.com/blog/advanced-shiny-tips/)
  * [Blog Post:  How to get your very own RStudio Server and Shiny Server with DigitalOcean](http://deanattali.com/2015/05/09/setup-rstudio-shiny-server-digital-ocean/)
  * [Blog Post: Mimicking a Google Form with a shiny app](http://deanattali.com/2015/06/14/mimicking-google-form-shiny/)
  * [Blog post: Persistent data storage (and retrieval) in Shiny apps](http://deanattali.com/blog/shiny-persistent-data-storage/)
  * [Blog post: How to set-up shiny server on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-shiny-server-on-ubuntu-14-04)
  * [Course: Stat545](http://stat545.com/)
* [Joe Cheng](https://medium.com/@joe.cheng)
  * [Async programming in R and Shiny](https://medium.com/@joe.cheng/async-programming-in-r-and-shiny-ebe8c5010790)
  * [An informal intro to async Shiny](https://medium.com/@joe.cheng/an-informal-intro-to-async-shiny-cbf01c85c4c5)
* [Alyssa Columbus](https://alyssacolumbus.com)
  * [Blog Post: Introduction to R Shiny](https://opendatascience.com/introduction-to-r-shiny/)
* [Abhinav Agrawal (YouTube)](https://www.youtube.com/playlist?list=PL6wLL_RojB5xNOhe2OTSd-DPkMLVY9DfB)
* [AHmed HAsan (YouTube)](https://www.youtube.com/playlist?list=PLXiYeGj1hvHN5Nnu2VwRg_E-YMoc1vtan)
* [Zev-Ross](http://zevross.com/blog/2016/04/19/r-powered-web-applications-with-shiny-a-tutorial-and-cheat-sheet-with-40-example-apps/)
* [Cheat Sheet](https://www.rstudio.com/resources/cheatsheets/#shiny)
* [Delivering Data Science for the Enterprise with Shiny in Kubernetes](https://blog.kublr.com/delivering-data-science-for-the-enterprise-with-shiny-r-in-kubernetes-8430c88d1b52)
* [Shiny Server on Docker: CentOS 7 Edition](http://www.datascienceriot.com/r/shiny-docker/)
* [Use Docker to distribute and run Shiny apps](https://wabi-wiki.scilifelab.se/display/KB/Use+Docker+to+distribute+and+run+Shiny+apps)
* [Dockerizing a Shiny App](http://www.rmining.com.br/2015/04/30/dockerizing-a-shiny-app/index.html)
* [Cookie based authentication with Shiny](https://calligross.de/post/using-cookie-based-authentication-with-shiny/)
* [Speed Up Shiny Coding with Data](https://roh.engineering/post/speeding-up-shiny-coding-with-data/)

## Tools

### Packages

* [golem](https://github.com/ThinkR-open/golem/) ⭐ 945 | 🐛 21 | 🌐 R | 📅 2026-07-07 - Framework for building production-grade shiny applications.
* [shinyWidgets](https://github.com/dreamRs/shinyWidgets) ⭐ 871 | 🐛 116 | 🌐 R | 📅 2026-07-06 - Extend input widgets available in Shiny.
* [shinyjs](https://github.com/daattali/shinyjs) ⭐ 751 | 🐛 5 | 🌐 R | 📅 2026-08-11 - Common JavaScript operations in shiny via R code.
* [timevis](https://github.com/daattali/timevis/) ⭐ 683 | 🐛 4 | 🌐 R | 📅 2024-08-18 - Create interactive timeline visualizations in R.
* [shiny.semantic](https://github.com/Appsilon/shiny.semantic) ⭐ 513 | 🐛 40 | 🌐 R | 📅 2025-12-02 - Semantic UI wrapper for Shiny.
* [waiter](https://github.com/JohnCoene/waiter) ⭐ 495 | 🐛 35 | 🌐 JavaScript | 📅 2026-08-17 - Loading screens for Shiny.
* [radiant](https://github.com/radiant-rstats/radiant) ⭐ 466 | 🐛 37 | 🌐 HTML | 📅 2026-01-10 - Business analytics using R and Shiny.
* [shinyauthr](https://github.com/PaulC91/shinyauthr) ⭐ 439 | 🐛 14 | 🌐 R | 📅 2024-03-04 - Server-side authentication using shiny modules.
* [shinycssloaders](https://github.com/daattali/shinycssloaders) ⭐ 422 | 🐛 3 | 🌐 CSS | 📅 2025-08-14 - Add CSS loader animations to Shiny outputs.
* [shinymanager](https://github.com/datastorm-open/shinymanager/) ⭐ 404 | 🐛 53 | 🌐 HTML | 📅 2026-07-06 - Simple and secure authentication for single 'Shiny' applications using a SQLite database.
* [dashboardthemes](https://github.com/nik01010/dashboardthemes) ⚠️ Archived - An experimental R package to provide custom theme options for Shinydashboard applications.
* [shinyjqui](https://github.com/Yang-Tang/shinyjqui) ⭐ 279 | 🐛 16 | 🌐 R | 📅 2023-12-30 - jQuery UI interactions and effects for shiny.
* [ggedit](https://github.com/metrumresearchgroup/ggedit) ⭐ 252 | 🐛 2 | 🌐 HTML | 📅 2024-05-11 - A Shiny gadget for exploring ggplot objects.
* [shinyalert](https://github.com/daattali/shinyalert) ⭐ 245 | 🐛 5 | 🌐 R | 📅 2024-06-02 - Easily create pretty popup messages (modals) in Shiny
* [polished](https://github.com/Tychobra/polished) ⭐ 236 | 🐛 21 | 🌐 R | 📅 2025-03-20 - Authentication, user administration, and web hosting for secure Shiny apps & Rmarkdown documents (flexdashboards, HTML, & PDF).
* [shinymaterial](https://github.com/ericrayanderson/shinymaterial) ⭐ 234 | 🐛 43 | 🌐 R | 📅 2025-12-23 - Implements Google Material Design in Shiny Applications.
* [shinyAce](https://github.com/trestletech/shinyAce) ⭐ 227 | 🐛 14 | 🌐 R | 📅 2025-02-02 - Integrate ace editor with shiny.
* [colourpicker](https://github.com/daattali/colourpicker) ⭐ 227 | 🐛 4 | 🌐 JavaScript | 📅 2024-08-18 - Colour picker widget that can be used in different contexts in R.
* [shinytest](https://github.com/rstudio/shinytest) ⭐ 224 | 🐛 53 | 🌐 JavaScript | 📅 2024-05-28 - Automated testing for shiny apps.
* [shinyFiles](https://github.com/thomasp85/shinyFiles) ⭐ 206 | 🐛 36 | 🌐 JavaScript | 📅 2023-07-05 - Extends the functionality of shiny by providing an API for client side access to the server file system.
* [shinysense](https://github.com/nstrayer/shinysense) ⭐ 205 | 🐛 19 | 🌐 JavaScript | 📅 2019-10-15 - Series of Shiny modules to help Shiny sense the world around it.
* [shinyFeedback](https://github.com/merlinoa/shinyFeedback) ⭐ 193 | 🐛 13 | 🌐 R | 📅 2023-01-31 - Display user feedback along side Shiny inputs.
* [ShinySky](https://github.com/AnalytixWare/ShinySky) ⭐ 188 | 🐛 20 | 🌐 R | 📅 2020-02-27 - Various UI widgets/components not part of Shiny e.g. alerts, styled buttons.
* [shinyforms](https://github.com/daattali/shinyforms) ⭐ 166 | 🐛 29 | 🌐 R | 📅 2022-02-13 - Easily create questionnaire-type forms with Shiny.
* [auth0](https://github.com/curso-r/auth0) ⭐ 165 | 🐛 31 | 🌐 R | 📅 2026-04-13 - Authentication in Shiny apps using Auth0 service.
* [shinyTree](https://github.com/shinyTree/shinyTree) ⭐ 153 | 🐛 35 | 🌐 JavaScript | 📅 2025-10-02 - Enables Shiny application developers to use the jsTree library in their applications.
* [bsplus](https://github.com/ijlyttle/bsplus) ⭐ 150 | 🐛 44 | 🌐 R | 📅 2025-04-06 - Shiny and R Markdown addons to Bootstrap 3.
* [shinybusy](https://github.com/dreamRs/shinybusy) ⭐ 146 | 🐛 12 | 🌐 R | 📅 2024-09-17 - Minimal busy indicator for Shiny apps.
* [yonder](https://github.com/nteetor/yonder) ⭐ 136 | 🐛 26 | 🌐 R | 📅 2026-08-23 - A reactive web framework built on shiny.
* [ECharts2Shiny](https://github.com/XD-DENG/ECharts2Shiny) ⭐ 131 | 🐛 6 | 🌐 R | 📅 2020-10-02 - Insert interactive charts from ECharts into Shiny.
* [reactlog](https://github.com/rstudio/reactlog) ⭐ 131 | 🐛 26 | 🌐 JavaScript | 📅 2026-08-24 - Visual insight into a Shiny apps reactive graph.
* [shinycustomloader](https://github.com/emitanaka/shinycustomloader) ⭐ 121 | 🐛 8 | 🌐 R | 📅 2018-07-17 - Add a custom loader for R Shiny.
* [shinyhelper](https://github.com/cwthom/shinyhelper) ⭐ 116 | 🐛 14 | 🌐 R | 📅 2022-10-05 - Add markdown help files to Shiny apps.
* [shinytoastr](https://github.com/MangoTheCat/shinytoastr) ⭐ 96 | 🐛 0 | 🌐 R | 📅 2016-08-29 - Notifications in Shiny, via [toastr](https://github.com/CodeSeven/toastr) ⭐ 12,103 | 🐛 154 | 🌐 JavaScript | 📅 2023-02-27.
* [shinyDND](https://github.com/ayayron/shinydnd) ⭐ 93 | 🐛 5 | 🌐 R | 📅 2017-09-24 - Create Shiny drag and drop elements in R.
* [shiny.collections](https://github.com/Appsilon/shiny.collections) ⭐ 75 | 🐛 4 | 🌐 R | 📅 2023-12-15 - Google Docs-like live collaboration in Shiny.
* [shinyscreenshot](https://github.com/daattali/shinyscreenshot) ⭐ 72 | 🐛 4 | 🌐 R | 📅 2024-10-27 - Capture screenshots of entire pages or parts of pages in Shiny apps
* [shinydisconnect](https://github.com/daattali/shinydisconnect) ⭐ 71 | 🐛 5 | 🌐 R | 📅 2024-08-18 - Show a nice message when a Shiny app disconnects or errors
* [supreme](https://github.com/strboul/supreme) ⚠️ Archived - Structure Shiny applications developed with modules.
* [reactor](https://github.com/yonicd/reactor) ⭐ 58 | 🐛 1 | 🌐 R | 📅 2021-07-07 - Unit testing for shiny reactivity
* [directoryInput](https://github.com/wleepang/shiny-directory-input) ⭐ 49 | 🐛 5 | 🌐 R | 📅 2021-03-03 - Widget for interactive selection of directories.
* [systemPipeShiny](https://github.com/systemPipeR/systemPipeShiny) ⭐ 36 | 🐛 0 | 🌐 R | 📅 2025-05-20 - Design/run biological or general data analysis workflows, and visualize downstream results.
* [shinyTime](https://github.com/burgerga/shinyTime) ⭐ 31 | 🐛 8 | 🌐 R | 📅 2024-05-08 - A timeInput widget for Shiny
* R-Studio
  * [shinydashboard](https://github.com/rstudio/shinydashboard) ⭐ 927 | 🐛 165 | 🌐 CSS | 📅 2025-04-22 - Shiny Dashboarding framework.
  * [fontawesome](https://github.com/rstudio/fontawesome) ⭐ 300 | 🐛 9 | 🌐 R | 📅 2025-10-05 - Easily insert FontAwesome icons into R Markdown docs and Shiny apps.
  * [shinythemes](https://github.com/rstudio/shinythemes) ⭐ 160 | 🐛 6 | 🌐 R | 📅 2022-02-25 - Bootstrap themes for use with Shiny.
    * [miniUI](https://github.com/rstudio/miniUI) ⭐ 108 | 🐛 6 | 🌐 R | 📅 2025-04-17 - Provides UI widget and layout functions for writing Shiny apps that work well on small screens.
* [shinystan](http://mc-stan.org/interfaces/shinystan) - Provides visual and numerical summaries of model parameters and convergence diagnostics for MCMC simulations.
* [RinteRface](https://rinterface.com) - A collection of HTML templates for Shiny.

### Integrations

* [ggvis](https://github.com/rstudio/ggvis) ⚠️ Archived - Make it easy to describe interactive web graphics in R.
* [googleVis](https://github.com/mages/googleVis) ⭐ 362 | 🐛 33 | 🌐 R | 📅 2025-10-08 - An interface between R and the [Google's charts tools](https://developers.google.com/chart/).
* [RInno](https://github.com/ficonsulting/RInno) ⭐ 313 | 🐛 61 | 🌐 HTML | 📅 2023-10-31 - Install local shiny apps by providing an interface between R and Inno Setup, (Windows Only).
* [pool](https://github.com/rstudio/pool) ⭐ 255 | 🐛 3 | 🌐 R | 📅 2026-05-19 - Abstract away the logic of connection management and the performance cost of fetching a new connection from a remote database.
* [HTML Widgets/JavaScript](http://www.htmlwidgets.org/)
  * [plotly](https://github.com/ropensci/plotly) ⭐ 2,677 | 🐛 760 | 🌐 R | 📅 2026-07-25 - Easily translate your ggplot2 graphics to an interactive web-based version, and also provides bindings to the plotly.js graphing library.
  * [DiagrammeR](https://github.com/rich-iannone/DiagrammeR) ⭐ 1,740 | 🐛 172 | 🌐 R | 📅 2026-04-27 - Tool for creating diagrams and flowcharts using Graphviz and Mermaid.
  * [networkD3](https://github.com/christophergandrud/networkD3) ⭐ 660 | 🐛 82 | 🌐 R | 📅 2025-04-18 - Graph data visualization with D3.
  * [echarts4r](https://github.com/JohnCoene/echarts4r) ⭐ 628 | 🐛 179 | 🌐 R | 📅 2026-06-23 - Create interactive charts by leveraging Echarts.js library.
  * [flextable](https://github.com/davidgohel/flextable) ⭐ 626 | 🐛 10 | 🌐 R | 📅 2026-08-05 - Easily create customizable tables
  * [DT](https://github.com/rstudio/DT) ⭐ 621 | 🐛 207 | 🌐 JavaScript | 📅 2026-05-18 - Provides a function `datatable()` to display R data via the DataTables JavaScript library.
  * [visNetwork](https://github.com/datastorm-open/visNetwork) ⭐ 564 | 🐛 156 | 🌐 JavaScript | 📅 2026-07-15 - Network visualization for R using vis.js library.
  * [rhandsontable](https://github.com/jrowen/rhandsontable) ⭐ 389 | 🐛 166 | 🌐 HTML | 📅 2024-07-23 - An htmlwidgets implementation of Handsontable.js.
  * [dygraphs](https://github.com/rstudio/dygraphs) ⭐ 367 | 🐛 122 | 🌐 JavaScript | 📅 2024-03-15 - R interface to the dygraphs JavaScript charting library. It provides rich facilites for charting time-series data in R.
  * [rthreejs](https://github.com/bwlewis/rthreejs) ⭐ 308 | 🐛 37 | 🌐 JavaScript | 📅 2025-05-03 - 3D scatterplots and globes.
  * [trelliscopejs](https://github.com/hafen/trelliscopejs/) ⭐ 263 | 🐛 77 | 🌐 R | 📅 2026-01-14 - TrelliscopeJS R package.
  * [d3heatmap](https://github.com/rstudio/d3heatmap) ⭐ 236 | 🐛 45 | 🌐 R | 📅 2025-11-29 - Implements a D3 heatmap htmlwidget.
  * [gglabeller](https://github.com/AliciaSchep/gglabeller) ⭐ 188 | 🐛 1 | 🌐 R | 📅 2021-03-12 - Gadget that enables selecting points on a ggplot to label.
  * [billboarder](https://github.com/dreamRs/billboarder) ⭐ 177 | 🐛 11 | 🌐 R | 📅 2026-08-06 - Htmlwidget for billboard.js.
  * [slickR](https://github.com/metrumresearchgroup/slickR) ⭐ 162 | 🐛 19 | 🌐 JavaScript | 📅 2025-12-15 - Slick carousel htmlwidget for R.
  * [scatterD3](https://github.com/juba/scatterD3) ⭐ 162 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-05 - Scatter plot htmlwidget based on D3.js.
  * [excelR](https://github.com/Swechhya/excelR) ⭐ 154 | 🐛 31 | 🌐 JavaScript | 📅 2023-07-12 - An interface to jExcel.js library.
  * [rintrojs](https://github.com/carlganz/rintrojs) ⭐ 137 | 🐛 20 | 🌐 R | 📅 2024-01-11 - Wrapper for the Intro.js library.
  * [manipulateWidget](https://github.com/rte-antares-rpackage/manipulateWidget) ⭐ 131 | 🐛 18 | 🌐 R | 📅 2026-01-16 - Add More Interactivity to htmlWidgets.
  * [MetricsGraphics](https://github.com/hrbrmstr/metricsgraphics) ⭐ 130 | 🐛 22 | 🌐 HTML | 📅 2018-02-03 - Enables easy creation of D3 scatterplots, line charts, and histograms.
  * [leaflet.minicharts](https://github.com/rte-antares-rpackage/leaflet.minicharts) ⭐ 108 | 🐛 26 | 🌐 R | 📅 2025-10-29 - Add and update small charts on an interactive leaflet maps.
  * [sigmajs](https://github.com/JohnCoene/sigmajs) ⭐ 72 | 🐛 7 | 🌐 R | 📅 2021-01-29 - Fully-fledged wrapper for the sigma.js JavaScript library.
  * [rclipboard](https://github.com/sbihorel/rclipboard) ⭐ 51 | 🐛 0 | 🌐 R | 📅 2023-11-15 - Clipboard.js for R/Shiny Applications.
  * [Crosstalk](https://rstudio.github.io/crosstalk/shiny.html) - Extends htmlwidgets with functionality for implementing cross-widget interactions.
  * [leaflet](http://rstudio.github.io/leaflet/shiny.html) - JavaScript library for creating dynamic maps that support panning and zooming along with various annotations like markers, polygons, and popups.
  * [rbokeh](http://hafen.github.io/rbokeh/) - Interface to Bokeh that provides a flexible, powerful, declarative framework for creating interactive plots.
  * [formattable](https://renkun.me/formattable/) - This package is designed for applying formatting on vectors and data frames to make data presentation easier, richer, more flexible and hopefully convey more information.
  * [highcharter](http://jkunst.com/highcharter/index.html) - Flexible JavaScript charting libraries in shiny.
* [flexdashboard](http://rmarkdown.rstudio.com/flexdashboard/index.html) - Easy interactive dashboards for R.
* [Shiny in Rmarkdown](http://rmarkdown.rstudio.com/authoring_shiny.html) - Run shiny apps in rmarkdown documents.

## People

* [Dean Attali](https://github.com/daattali)
* [Joe Cheng](https://github.com/jcheng5)
* [Winston Chang](https://github.com/wch)
* [Barbara Borges Ribeiro](https://github.com/bborgesr)
* [Ramnath Vaidyanathan](https://github.com/ramnathv)
* [Jeff Allen](https://github.com/trestletech)
* [Vincent Nijs](https://github.com/vnijs)
* [Sebastian Kranz](https://github.com/skranz)
* [David Granjon](https://divadnojnarg.github.io)

## Books

* [Web Application and Development Using Shiny (2nd edition) - by Chris Beely](https://www.amazon.com/Web-Application-Development-using-Shiny/dp/1782174346)
* [Learing Shiny - by Hernán G. Resnizky](https://www.amazon.com/Learning-Shiny-Hernan-G-Resnizky/dp/1785280902)
* [(WIP) Mastering Shiny - by Hadley Wickham](https://mastering-shiny.org/)
* [Engineering Production-grade Shiny Apps - by Colin Fay, Sébastien Rochette, Vincent Guyader, Cervan Girard](https://www.amazon.fr/Engineering-Production-grade-Shiny-Apps-Colin/dp/0367466023/ref=tmm_pap_swatch_0?_encoding=UTF8\&qid=\&sr=)

## Galleries

* R-Studio
  * [Shiny User Showcase](https://www.rstudio.com/products/shiny/shiny-user-showcase/) - Featured user Shiny apps.
  * [Shiny Gallery](https://shiny.rstudio.com/gallery/) - Shiny apps and much more.
* [Showmeshiny](http://www.showmeshiny.com/) - Huge gallery of Shiny apps.
* [Shiny Widgets](http://shinyapps.org/) - Experience statistics with apps designed for teaching and analysis.
* Html Widgets
  * [Html Widgets Showcase](http://www.htmlwidgets.org/showcase_leaflet.html) - Featured Html widgets.
  * [Html Widgets Gallery](http://gallery.htmlwidgets.org/) - User submitted Html widgets.
* [R Graph Catalog](http://shinyapps.stat.ubc.ca/r-graph-catalog/) - Complement to the book  “Creating More Effective Graphs” by Naomi Robbins.
* [Awesome Shiny Apps for Statistics](https://github.com/huyingjie/Awesome-shiny-apps-for-statistics) ⭐ 179 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-10 - A curated list of awesome Shiny Apps for statistics.

## App Examples

* [R-Studio Examples](https://github.com/rstudio/shiny-examples) ⭐ 2,036 | 🐛 55 | 🌐 JavaScript | 📅 2025-05-20
* [BallR](https://github.com/toddwschneider/ballr) ⭐ 613 | 🐛 2 | 🌐 R | 📅 2022-12-30 - Uses the NBA Stats API to visualize every shot taken by a player during an NBA season dating back to 1996.
* [shinyEd](https://github.com/ShinyEd/ShinyEd) ⭐ 246 | 🐛 1 | 🌐 R | 📅 2022-09-15 - Statistics education apps.
* [shiny-salesman](https://github.com/toddwschneider/shiny-salesman) ⭐ 245 | 🐛 0 | 🌐 R | 📅 2019-02-18 - Traveling salesman app.
* [Google Analytics Dashboard](https://github.com/MarkEdmondson1234/ga-dashboard-demo) ⭐ 124 | 🐛 5 | 🌐 R | 📅 2018-04-20 - Demo on how to build your own Google Analytics dashboard with R, Shiny and MySQL.
* [STARTapp](https://github.com/jminnier/STARTapp) ⭐ 87 | 🐛 7 | 🌐 HTML | 📅 2020-11-11 - Transcriptome Analysis Resource Tool.
* [shiny-phyloseq](https://github.com/joey711/shiny-phyloseq) ⭐ 60 | 🐛 22 | 🌐 HTML | 📅 2019-07-18 - Provides a graphical user interface to the microbiome analysis package for R, called phyloseq.
* [Interactive PCA Explorer](https://github.com/benmarwick/Interactive_PCA_Explorer) ⭐ 55 | 🐛 1 | 🌐 R | 📅 2023-12-21 - Explore a PCA plots and data.
* [NYT Bar Optimizer](https://github.com/jordanmeyer/nyt-bar-optimizer) ⭐ 41 | 🐛 2 | 🌐 R | 📅 2016-02-14 - Optimize your liquor cabinet using cocktail recipes from New York Times Cooking.
* [R Shiny User Management & Authentication](https://github.com/yanirmor/shiny-user-management) ⭐ 39 | 🐛 4 | 🌐 R | 📅 2023-01-10 - Demonstration of user management and authentication system in R Shiny.
* [html2r](https://github.com/alandipert/html2r) ⚠️ Archived - Convert HTML to R.
* [MAVIS](https://github.com/kylehamilton/MAVIS) ⭐ 36 | 🐛 5 | 🌐 R | 📅 2018-03-01 - MAVIS: Meta Analysis via Shiny.
* [Shiny GEM](https://github.com/dm3ll3n/Shiny-GEM) ⭐ 22 | 🐛 0 | 🌐 R | 📅 2019-05-06 - GEM stands for ‘general exploratory methods’, as this app aims to simplify a variety of basic EDA tasks.
* [GenMap-Comparator](https://github.com/holtzy/GenMap-Comparator) ⭐ 22 | 🐛 2 | 🌐 R | 📅 2023-02-28 - Compare genetic maps with D3 & Shiny.
* [ExpressionDB](https://github.com/5c077/ExpressionDB) ⭐ 17 | 🐛 0 | 🌐 R | 📅 2018-01-08 - Host gene expression/ontology data with Shiny.
* [vinylSpotting](https://github.com/ewenme/vinylspotting) ⭐ 13 | 🐛 1 | 🌐 R | 📅 2019-05-11 - Visualize and explore Discogs record collections.
* [OCRinShiny](https://github.com/longhowlam/OCRinShiny) ⭐ 13 | 🐛 2 | 🌐 R | 📅 2020-02-10 - OCR an image with the tesseract package.
* [contributr](https://github.com/LucyMcGowan/contributr) ⭐ 12 | 🐛 8 | 🌐 R | 📅 2017-04-27 - Find beginner GitHub issues to contribute to.
* [taskviewr](https://github.com/bearloga/taskviewr) ⭐ 11 | 🐛 0 | 🌐 R | 📅 2019-09-04 - Browse R packages by CRAN Task Views and license info.
* [iTunes Reviews Analysis](https://github.com/amrrs/itunesr_webapp) ⭐ 10 | 🐛 1 | 🌐 R | 📅 2020-03-03 - iTunes App Store Reviews Text Extractor and Text Analysis Web App.
* [Shiny App Spotify](https://github.com/joelcponte/shiny-app-spotify) ⭐ 10 | 🐛 1 | 🌐 R | 📅 2018-03-07 - Connect with spotify's API and generate personalized playlist recommendations through machine learning and data visualization.
* [VisualPruner](https://github.com/LaurenSamuels/VisualPruner) ⭐ 4 | 🐛 0 | 🌐 HTML | 📅 2023-02-09 - Cohort selection in observational studies.
* [Opioid Overdose Shiny App](https://github.com/Dmunslow/Opioid-Overdose-Shiny-App) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2018-03-12 - Visualize opioid overdose data.
* [Waze](https://www.rstudio.com/resources/customer-spotlight/waze_story/) - Community based real-time traffic and navigation info.
* [Astra Zeneca](https://www.rstudio.com/resources/customer-spotlight/astra_zeneca/) - Data science tools used to create medicines more efficiently.
* [shiny-ampvis2](https://kasperskytte.shinyapps.io/shinyampvis) - Provides some basic functionality for using ampvis2 to visualize microbiome data.
* [Lights Out game](https://daattali.com/shiny/lightsout/) - Lights Out is a puzzle game consisting of a grid of lights that are either on or off.
* Australian Tax Office:
  * [Workforce Demographics](https://atogov.shinyapps.io/workforcedmgs/) - View a range of workforce related demographics information across an organisation. [Source Code](https://github.com/atogov/workforceDmgs).
  * [Bivariate Demographics](https://atogov.shinyapps.io/bivariatedmgs/) - Examine how an organisation is performing on a range of demographic information. [Source Code](https://github.com/atogov/bivariateDmgs).
* [Shiny Database App (CRUD)](https://ipub.com/dev-corner/apps/shiny_crud01/) - An example of a [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) shiny app with [accompanying how-to post](https://ipub.com/shiny-crud-app/).
* [homebrewR](https://davesteps.shinyapps.io/homebrewR/) - Explore and compare beer recipes.
* [polMonitor](https://ewenme.shinyapps.io/polMonitor/) - Monitor police violence in the United States.
* [National Parks Weather](https://github.com/sgaraycoa/National-Parks-Weather) - Visualize National Parks locations and weather using user input.
* [Anomaly Detection](https://murat-koptur.shinyapps.io/AnomalyDetectionShiny/) - Detect anomalies on univariate timeseries data using AnomalyDetection package.

## Contributors

[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/0)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/0)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/1)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/1)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/2)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/2)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/3)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/3)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/4)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/4)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/5)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/5)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/6)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/6)[![](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/images/7)](https://sourcerer.io/fame/grabear/grabear/awesome-rshiny/links/7)

* [Rob Gilmore](https://github.com/grabear)
* [Shaurita Hutchins](https://github.com/sdhutchins)
* [Devin Pastoor](https://github.com/dpastoor)
* [Dean Attali](https://github.com/daattali)
* [Luke Singham](https://github.com/ucg8j)
* [Abdul Majed Raja](https://www.github.com/amrrs)
* [Leonardo Trimarchi](https://domthecodingcaveman.wordpress.com/)
* [Kshitiz Khanal](http://twitter.com/kshitizkhanal7)
* [Alyssa Columbus](https://alyssacolumbus.com)
* [Patrick Howard](https://polished.tech)
* [Le Zhang](https://github.com/lz100)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
