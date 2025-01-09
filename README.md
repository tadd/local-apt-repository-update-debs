local-apt-repository-update-debs
================================

Automatically fetches and updates 3rd-party's `*.deb` files for
[local-apt-repository](https://salsa.debian.org/debian/local-apt-repository).

## Usage

1. Install `local-apt-repository` [package](https://packages.debian.org/stable/local-apt-repository).
2. Copy files via

    ```bash
    sudo cp update-debs update-debs-source.conf /usr/lib/local-apt-repository/
    ```

3. Call `/usr/lib/local-apt-repository/update-debs` periodically with cron or systemd.

## License

[MIT.](./LICENSE.md)
