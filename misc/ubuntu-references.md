# Bash References

<details>

<summary><a href="https://dba.stackexchange.com/a/303671">Ubuntu Check a particular package installed</a></summary>

```sh
dpkg --list|grep mysql
sudo apt-get remove mysql-common
sudo apt-get autoremove --purge mysql-server-"version"
dpkg -l|grep ^rc|awk '{print$2}'|sudo xargs dpkg -P
dpkg --list|grep mysql
sudo apt-get autoremove --purge mysql-apt-config
```

</details>

* [How do I disable MySQL on Linux from starting on boot or statup?](https://dba.stackexchange.com/a/231761)
