# mod_ssl-npn
Apache 2.4.17's NPN patch for mod_ssl

Based on mod-spdy's patch, but we use `patch -p1 < npn.patch`

<hr>

#####IMPORTANT NOTE: 

NPN and mod_spdy is deprecated, this patch is just for testing.

It is strongly recommended that you use mod_h2, which is included in httpd since Apache 2.4.17.

Not tested with mod_spdy, use at your own risk.

mod_h2 will not advertise h2 through NPN, but only ALPN

Issues and PRs are welcomed.
