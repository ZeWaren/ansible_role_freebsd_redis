# ansible-freebsd-redis

## Introduction
This is an extremely simple role that just installs `redis` on FreeBSD.

## Variables

See [defaults/main.yml](defaults/main.yml) for the default values of each.

### redis_enabled

Determine if `redis_enable` is set to `"YES"` or `"NO"` in `/etc/rc.conf`.

### redis_started

Determine if the service should be started or not.

## Dependencies

None.

## Licence

BSD

## Author

[Erwan Martin](https://zewaren.net/)
