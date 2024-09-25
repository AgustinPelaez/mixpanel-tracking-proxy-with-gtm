**NOTE:** I use Mixpanel's GTM template, but it doesn't work with the proxy approach because the required library is not proxied by default in Mixpanel's original [Nginx Proxy for Mixpanel](https://github.com/mixpanel/tracking-proxy) project. So I had to create this fork and simply add the lines to the nginx.conf file.

Click on a button below to deploy to your favorite cloud provider:

[![Google Cloud Btn]][Google Cloud Deploy]
[<img src=https://www.deploytodo.com/do-btn-blue.svg width=198px />][Digital Ocean Deploy]
[![Railway Btn]][Railway Deploy]
[![Render Btn]][Render Deploy]


<!-- URLS -->
[Digital Ocean Btn]: https://www.deploytodo.com/do-btn-blue.svg
[Digital Ocean Deploy]: https://cloud.digitalocean.com/apps/new?repo=https://github.com/AgustinPelaez/mixpanel-tracking-proxy-with-gtm/tree/master

[Render Btn]: https://binbashbanana.github.io/deploy-buttons/buttons/remade/render.svg
[Render Deploy]: https://render.com/deploy?repo=https://github.com/AgustinPelaez/mixpanel-tracking-proxy-with-gtm

## GTM configuration
Once you've setup your custom domain, go to Mixpanel template and replace the current library URL in two (2) places:

1- Replace library URL in Mixpanel's template code:
![image](https://github.com/user-attachments/assets/22517234-bde2-40bd-aabb-769f719f6891)

2- Replace library URL in Mixpanel's template permissions tab:
![image](https://github.com/user-attachments/assets/d6077120-30c8-4168-b03e-dc7f6e5fcfec)
