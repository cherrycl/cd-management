$$./common/warning.md

$$./common/quick-reference.md

# Supported tags and respective Dockerfile links

$$./common/version-napa.md |
        - [Dockerfile](https://github.com/edgexfoundry/security-spiffe-token-provider/blob/v3.1.0/Dockerfile)
$$./common/version-minnesota.md |
        - [Dockerfile](https://github.com/edgexfoundry/security-spiffe-token-provider/blob/v3.0.0/Dockerfile)
$$./common/version-levski.md |
        - [Dockerfile](https://github.com/edgexfoundry/security-spiffe-token-provider/blob/v2.3.0/Dockerfile)
$$./common/version-kamakura.md |
        - [Dockerfile](https://github.com/edgexfoundry/security-spiffe-token-provider/blob/v2.2.0/Dockerfile)

# Quick reference 

- Where to file issues: https://github.com/edgexfoundry/security-spiffe-token-provider/issues
- Supported architectures: intel/amd64
- Source of this description: https://github.com/edgexfoundry/cd-management/tree/edgex-docker-hub-documentation/image-overview-templates/new-names/security-spiffe-token-provider.md

$$./common/what-is-edgex.md

# What's in this image?

This image contains a microservice that [enables security for remote device services](https://docs.edgexfoundry.org/2.2/security/Ch-RemoteDeviceServices/)
and delayed-start microservices that cannot have an EdgeX secret token pre-seeded to the microservice.
This service works by exchanging a [SPIFFE](https://spiffe.io/) X.509 SVID for an EdgeX secret store token.
This is necessary when EdgeX is running in security-enabled mode in order to access the EdgeX secret store,
the EdgeX secure message bus, the EdgeX registry provider, and the EdgeX configuration provider services.

Source code for security-spiffe-token-provider: <https://github.com/edgexfoundry/edgex-go/>

$$./common/license.md
