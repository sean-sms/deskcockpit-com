# deskcockpit.com

Forwards deskcockpit.com to Desk Cockpit's page on the SMS Apps site,
https://sms-apps.com/deskcockpit/, keeping the page: `/support` and `/privacy` go to
their pages there, and anything else to the main page. GitHub Pages (custom domain in
`CNAME`) supplies the HTTPS that `.app` domains require; `404.html` handles every path
other than the root.

DNS at Bluehost for deskcockpit.com: four `A` records for `@` (185.199.108.153,
185.199.109.153, 185.199.110.153, 185.199.111.153) and `www` as a `CNAME` to
`sean-sms.github.io`.
