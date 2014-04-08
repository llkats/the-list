the-list
========

a list of terrible websites to avoid

## Info

Hosts file explanation to be added. [http://en.wikipedia.org/wiki/Hosts_(file)](http://en.wikipedia.org/wiki/Hosts_(file))

## Motives

Avoid ethically or politically repugnant websites by adding them to your hosts file. Denying a site a pageview is somewhat akin to avoiding shopping at a store with terrible management. Additionally, it'll free your brain up from having to view potentially awful content.

## Install

the-list is easily added to your own hosts file by curling the-lists's text file.

By running this command in your terminal, the contents of [`list.txt`](https://raw.githubusercontent.com/llkats/the-list/master/list.txt)
will be appended to your `/etc/hosts` file.

```shell
curl -fsSL https://raw.githubusercontent.com/llkats/the-list/master/list.txt >> /etc/hosts
```

The flags are there to handle error cases more gracefully and safely handle redirects.
[See `man curl` for a more comprehensive explanation](https://github.com/llkats/the-list/pull/2#commitcomment-5936208).

## Pull Request Guidelines

Additions to the content or style of the-list are gratefully received. If suggesting a new site to be blocked, please update `index.html` with reference links and text explaining the motivations behind why a site should be blocked, as well as alternative resources in the case of news outlets.

## Inspirations

Other host file sites: [http://someonewhocares.org/hosts/](http://someonewhocares.org/hosts/) and [https://al3x.net/2009/09/14/my-get-back-to-work-hack.html](https://al3x.net/2009/09/14/my-get-back-to-work-hack.html)

## License
MIT
