# Debianization for the Erlang ekaf Library

The repo contains so called DEBIAN directory with
scripts and configs needed to package the
[ekaf](https://github.com/helpshift/ekaf/)
library into a DEB package for the Debian Wheezy distro.

A minimal, high-performance Kafka client in Erlang.
- An erlang implementation of a Producer as per 0.8 Kafka
  wire protocol;
- Produce to a Topic syncronously and asynchronously;
- Option to batch messages and customize the concurrency;
- Several lazy handling of both metadata requests as well as
  connection pool creation;
- Will automatically buffer when broker goes down and resend,
  with max downtime size configurable;
- Will automatically start/stop workers based on kafka broker
  additions/changes/downtime;
- Callbacks to instrument into your monitoring system.
