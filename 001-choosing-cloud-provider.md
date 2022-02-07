# Choosing a Cloud Provider

## Status

IN PROGRESS

## Description

We need to decide on a cloud provider/host for bosstones.net

### AWS

Pros
-  Most popular host
-  Lots of documentation
-  Tons of services (like EC2, RDS, S3) to leverage
Cons
- Stuck in AWS land

### GCP
Pros
- Not stuck in AWS land

Cons
- xtine has no knowledge of how GCP works lol

### Linode (on xtine's account)
Pros
- Account already setup
- Linode documentation we good
- Simpler

Cons
- No access to services available in AWS/GCP
- Already other things running in the linode


## Consequences

Once we decide on a cloud provider we have to stick with it for the long haul.
Unless we hit an absolute blocker in which we can't sustainly continue with our chosen provider, it's going to really suck having to re-learn, re-configure and re-provision all services in a new host.

## Decision

