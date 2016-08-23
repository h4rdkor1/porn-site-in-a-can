
# Porn Site in a Can

Ready to deploy and configure adult video site.  Or make a non-porn tube site out of it.

No porn included -- this is only code (and certainly not good enough code to be considered code porn).

Despite the name, these install instructions do require basic familiarity with editing code,
MySQL, and Linux.

## Features

* Automatic indexing, conversion, and thumbnailing of video files
* Leech protection
* Netflix style "users with similar taste also liked" recommendations
* 100% ready to receive Bitcoin payments out of the box
* Referal system with automatic, "instant" payouts
* One-click account creation (really!)
* Runs on cPanel powered shared hosts (except for referal payouts)

porn-site-list
==============

List of porn sites on the world

This repository contains lists of porn sites in JSON.

Currently lists of site, scrapping from [xxxindia.org](http://xxxindia.org/) and [xxxindia.org](http://xxxindia.org/)

I create this repo, because i want to list all (top) porn site, we when user submit link to your site, you cant check and prevent


### How to contribute?
- Just do [Pull request]https://github.com/aredo/porn-site-list/pulls and new site with JSON structure
```js
{
  "protocol": "http",
  "domain": "www.tube8.com",
  "path": null,
  "subdomain": "www",
  "host": "tube8",
  "tld": "com",
  "parent_domain": "tube8.com"
}
```
