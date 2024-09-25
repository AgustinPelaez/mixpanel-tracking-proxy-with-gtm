**NOTE:** I use Mixpanel's GTM template, but it doesn't work with this Proxy approach because the required library is not proxied by default in Mixpanel's original [Nginx Proxy for Mixpanel](https://github.com/mixpanel/tracking-proxy) project. So I had to create this fork and simply add the lines to the nginx.conf file.

[<img src=https://www.deploytodo.com/do-btn-blue.svg width=198px />][Digital Ocean Deploy]
[Digital Ocean Btn]: https://www.deploytodo.com/do-btn-blue.svg
[Digital Ocean Deploy]: https://cloud.digitalocean.com/apps/new?repo=https://github.com/AgustinPelaez/mixpanel-tracking-proxy-with-gtm/tree/master
