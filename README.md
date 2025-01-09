local-apt-repository-update-debs
================================

Automatically fetches and updates 3rd-party's `*.deb` files for
[local-apt-repository](https://salsa.debian.org/debian/local-apt-repository).

## Usage

1. Copy files via

    ```bash
    sudo cp update-debs update-debs-source.conf /usr/lib/local-apt-repository/
    ```

2. Call `/usr/lib/local-apt-repository/update-debs` periodically with cron or systemd.

## Dependency

```bash
sudo apt install bash local-apt-repository wget
```

## License

[MIT.](./LICENSE.md)
