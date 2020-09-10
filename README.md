UberFTP
=======

Interactive GridFTP client

UberFTP is a GridFTP-enabled client that supports both interactive use and FTP commands on the `uberftp` command line to transfer files between two computers. It is intended for use with computers that have a GridFTP server installed. UberFTP supports GSI authentication, parallel data channels and striping.

> **NOTICE:**
> UberFTP v2.9 uses `EPSV` and `EPRT` (see [RFC 2428](https://tools.ietf.org/html/rfc2428) for details) to support both IPv4 and IPv6 addresses. To maintain compatibility from a [Globus GridFTP](https://gridcf.org/gct-docs/latest/gridftp/index.html) service, use the configuration options `epsv_ip 1` and `epsv_match 1` for the PI (frontend process) of that service **if** its PI(s) and DTP(s) (backend process(es)) are located on different hosts.
