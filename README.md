# Urbit Systems Technical Journal Forum

Created by ~polwex for the Urbit Foundation.

##  Command-Line Interface

```hoon
> :ustj [%ui ~zod *@ta %submit-thread title='Google Dot Com' url='http://google.com' text='']

> :ustj [%ui ~rovnys-ricfer *@ta %submit-thread title='USTJv1i1 - Eight Years After the Whitepaper' url='https://urbitsystems.tech/article/v01-i01/eight-years-after-the-whitepaper' text='']

> :ustj [%ui ~magbel *@ta %auth ~magbel *@uv "0xae530A3D4bcD3B236F4227A4ADe2f462B802FA25" "0xae530A3D4bcD3B236F4227A4ADe2f462B802FA25"]
```

##  Login

1. Urbit OS login is managed by Eyre's EAuth system.
2. Urbit ID login is provisioned for MetaMask.  Two endpoints are exposed:
  1. `/metamask` to obtain the session secret (via `POST`).
  2. `/auth` to `POST` the authentication attempt.

---

- [ ] getting MetaMask script to kick off
- [ ] add “Hosted on Urbit” to footer
