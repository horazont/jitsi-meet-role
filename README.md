# jitsi-meet-role

## Description

Install jitsi-meet on a debian system from packages (not docker).

## Parameters

- `jitsi_hostname` (required): The hostname under which the Jitsi Meet instance is and will be reachable. This is used to obtain certificates and configure nginx and stuff.
- `jitsi_certbot` (default: true): If enabled, this will obtain certificates with certbot, though that’s currently buggy (grep for FIXME).
