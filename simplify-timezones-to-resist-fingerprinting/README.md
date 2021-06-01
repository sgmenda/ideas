# Simplify Timezones to Resist Fingerprinting

I posted the following to [`#privacy:mozilla.org`](https://matrix.to/#/!pwjZPJGiWfMMzbMCXJ:mozilla.org/$Z0a3lppjxjw-wspuGpcJ7GYadXNvwq5R_FEoDvfKlVU?via=mozilla.org&via=privacytools.io&via=kde.org) a few days ago,

> I am messing around with RFP's Timezone Spoofing and looking around I came across this really [cool idea](https://github.com/brave/brave-browser/issues/8574) by the brave folks to simplify timezones. So, my `America/Toronto` would be a more generic `Etc/GMT-4`; see also my comment on the post about picking the most popular timezone name (like `America/Toronto` becomes `America/New York`) to reduce breakage. It might be cool to do something similar in Firefox/ETP. I wrote a [quick and dirty patch](./simplify-timezones.patch) which shows that this is possible and if people are interested, I can write a better patch.
