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
-  Working in AWS could provide enough familiarity to obtain certs

Cons
- Stuck in AWS land
- Can lead to choice paralysis with so many options available
- JD doesn't know AWS

### GCP
Pros
- Not stuck in AWS land
- JD knows GCP
- Plenty of AWS equivalent services
- Lots of documentation
- Working in GCP could provide enough familiarity to obtain certs

Cons
- xtine has no knowledge of how GCP works lol
- Occasionally documentation is out of date and can be confusing.

### Linode (on xtine's account)
Pros
- Account already setup
- Linode documentation is good
- Simpler

Cons
- No access to services available in AWS/GCP
- Already other things running in the linode

### Azure
Pros
- Equal learning as none of us are too familiar
- Working in Azure could provide enough familiarity to obtain certs

Cons
- Least supported of the cloud providers
- Locked into Microsoft land for more than just cloud, also tools and possibly code choices.

## Consequences

Once we decide on a cloud provider we have to stick with it for the long haul.
Unless we hit an absolute blocker in which we can't sustainly continue with our chosen provider, it's going to really suck having to re-learn, re-configure and re-provision all services in a new host.

Counter point - By using Terraform to configure our infrastructure we will be able to change providers with some refactoring. Containerized code bases, CI/CD pipelines make the change annoying but not unwieldly. It wouldn't be easy but not a heraculean effort.

## Decision

