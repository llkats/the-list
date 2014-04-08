the-list
========

a list of terrible websites to avoid

## Install

This command appends [`list.txt`](https://raw.githubusercontent.com/llkats/the-list/master/list.txt)
to your `/etc/hosts` file. To prevent you from seeing them.

```shell
curl -fsSL https://raw.githubusercontent.com/llkats/the-list/master/list.txt >> /etc/hosts
```

The flags are there to handle error cases more gracefully and safely handle redirects.
[See `man curl` for a more comprehensive explanation](https://github.com/llkats/the-list/pull/2#commitcomment-5936208).

## License
MIT
