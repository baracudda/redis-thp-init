# redis-thp-init

Docker container build and supporting files, if any, for fixing the WARNING issue with Redis when executing on a host with THP support enabled.

> WARNING you have Transparent Huge Pages (THP) support enabled in your kernel.
>  This will create latency and memory usage issues with Redis.
>  To fix this issue run the command 'echo never > /sys/kernel/mm/transparent_hugepage/enabled' as root,
>  and add it to your /etc/rc.local in order to retain the setting after a reboot.
>  Redis must be restarted after THP is disabled.
