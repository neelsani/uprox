# uprox
A WebProxy built with Cloudflare Workers

## What does it do?
Visit mirrored sites via your domain / subdomain! It routes traffic of the sites you visit  and hides your IP and activities from the web. Any site you visit will appear to be (your domain) to your ISP and the computers that are handling your requests worldwide. Kinda like Tor or VPN but in my opinion more secure.

## Features
1. No dependencies, pure Javascript.
2. Changes Links inside the page.
3. Handles relative links.
4. Partial support for JavaScript Parsing inside webpages.
5. Requests archive.org to archive the pages you visit, anonymously.
6. Completely Anonymous. No logging.
7. Supports Ad-Blockers. Only changes links within the same base domain.

## Build
Simply fork the project and host it with Cloudflare Pages. It should work out of the box.

## Anti-Features
1. WebApps and complex sites might break.
2. Videos and Audios might not work.
3. Sites without https might not work. The Proxy tries to load pages in https: protocol only. Thus http: is not supported.


