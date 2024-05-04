# gpio-hg680p
- power
- infrared
- lan


## Instalation
HG680P
```
opkg update && (cd /tmp && curl -sLko install https://raw.githubusercontent.com/Houjie80/gpio-hg680p/3led/install && bash install)
```

rc.local:

```
/usr/bin/inet-hg680p.sh -r
```
B860h
```
opkg update && (cd /tmp && curl -sLko install https://raw.githubusercontent.com/Houjie80/gpio-hg680p/3led/B860h && bash B860h)
```

rc.local:

```
/usr/bin/bledon -r
```

### Credit

- Putra-0 ( GPIO MOD )
https://github.com/Putra-0/gpio-hg680p
- lutfailham96 https://github.com/lutfailham96/s905x-gpio
- miftakul.artanto (pin gpio IR )
  https://www.facebook.com/miftakul.artanto
