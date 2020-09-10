UberFTP
=======

Interactive GridFTP client

> **NOTICE:**
> UberFTP v2.9 uses `EPSV` and `EPRT` (see [RFC 2428](https://tools.ietf.org/html/rfc2428) for details) to support both IPv4 and IPv6 addresses. To maintain compatibility from a [Globus GridFTP](https://gridcf.org/gct-docs/latest/gridftp/index.html) service, use the configuration options `epsv_ip 1` and `epsv_match 1` for the PI (frontend process) of that service **if** its PI(s) and DTP(s) (backend process(es)) are located on different hosts.
