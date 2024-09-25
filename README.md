**NOTE:** I use Mixpanel's GTM template, but it doesn't work with this Proxy approach because the required library is not proxied by default in Mixpanel's original [Nginx Proxy for Mixpanel](https://github.com/mixpanel/tracking-proxy) project. So I had to create this fork and simply add the lines to the nginx.conf file.

Click on a button below to deploy to your favorite cloud provider:

[![Google Cloud Btn]][Google Cloud Deploy]
[<img src=https://www.deploytodo.com/do-btn-blue.svg width=198px />][Digital Ocean Deploy]
[![Railway Btn]][Railway Deploy]
[![Render Btn]][Render Deploy]


<!-- URLS -->
[Google Cloud Btn]: https://binbashbanana.github.io/deploy-buttons/buttons/remade/googlecloud.svg
[Google Cloud Deploy]: https://deploy.cloud.run

[Digital Ocean Btn]: https://www.deploytodo.com/do-btn-blue.svg
[Digital Ocean Deploy]: https://cloud.digitalocean.com/apps/new?repo=https://github.com/AgustinPelaez/mixpanel-tracking-proxy-with-gtm/tree/master

[Railway Btn]: https://binbashbanana.github.io/deploy-buttons/buttons/remade/railway.svg
[Railway Deploy]: https://railway.app/template/_RaWSW

[Render Btn]: https://binbashbanana.github.io/deploy-buttons/buttons/remade/render.svg
[Render Deploy]: https://render.com/deploy?repo=https://github.com/AgustinPelaez/mixpanel-tracking-proxy-with-gtm
