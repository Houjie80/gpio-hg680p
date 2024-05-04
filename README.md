# gpio-hg680p
- power
- infrared
- lan


## Instalation

```
opkg update && (cd /tmp && curl -sLko install https://raw.githubusercontent.com/Houjie80/gpio-hg680p/3led/install && bash install)
```

add crontab scheduled task to script work regularly at 12AM every day:

```
0 12 * * * /sbin/sync_time.sh bug.com
```

### Credit

- Putra-0 ( GPIO MOD )
https://github.com/Putra-0/gpio-hg680p
- lutfailham96 https://github.com/lutfailham96/s905x-gpio
- miftakul.artanto (pin gpio IR )
  https://www.facebook.com/miftakul.artanto
