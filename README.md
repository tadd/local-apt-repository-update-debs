local-apt-repository-update-debs
================================

Automatically fetches and updates 3rd-party's `*.deb` files for
[local-apt-repository](https://salsa.debian.org/debian/local-apt-repository).

## Usage

```bash
sudo cp update-debs update-debs-source.conf /usr/lib/local-apt-repository/
```

Then call `/usr/lib/local-apt-repository/update-debs` periodically with cron or systemd.

## License

[MIT.](./LICENSE.md)
