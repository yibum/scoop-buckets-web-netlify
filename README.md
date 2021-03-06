## Scoop Buckets Web (Unofficial)

[![Netlify Status](https://api.netlify.com/api/v1/badges/965df306-a386-4e0b-9351-ee2bdb712857/deploy-status)](https://scoop.airbrain.app)
<a href='https://ko-fi.com/J3J113VYZ' target='_blank'><img height='26' style='border:0px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

Is that app in [Scoop](https://scoop.sh) buckets? 
A simple web tool to ~~search~~ filter out apps in Scoop buckets (Main + Extra).

### More Info?
Typically one can search an app in Scoop by `scoop search <app-name>`, but it is sometimes slow on my local machine.

This website syncs all available apps from "well known" buckets,  Main and Exta, every a few hours and pushes it to Netlify.

Thanks
* [Scoop](https://scoop.sh)
* [Netlify](https://https://www.netlify.com/)
* [Zola](https://github.com/getzola/zola)
* [Bulma](https://bulma.io/)
* Github Action (on schedule hook with Netlify)

There are other buckets available: [Scoop wiki](https://github.com/lukesampson/scoop/wiki/Buckets). I may make other buckets available on the website in the future.

There is a legacy GatsbyJS implementation in [gatsbyjs branch](https://github.com/yibum/scoop-buckets-web-netlify/tree/gatsbyjs)

### Local Development
`zola serve`

### Posts
[中文](https://blog.yibu.org/posts/2020/04/11/netlify-scoop-search-deployment-rust-zola/) | [EN](https://blog.yibu.org/en/posts/2020/04/11/netlify-scoop-search-deployment-rust-zola/)
