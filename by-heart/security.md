# Security

## Authenticators

* Form Login
* JSON Login
* HTTP Basic
* Login Link
* X.509 Client Certificates
* Remote users
* Custom Authenticators

## Pseudo-Roles

* IS_AUTHENTICATED_FULLY
* IS_AUTHENTICATED_REMEMBERED
* IS_AUTHENTICATED
* IS_IMPERSONATOR
* IS_REMEMBERED
* PUBLIC_ACCESS

## Events

* CheckPassportEvent
* AuthenticationTokenCreatedEvent
* AuthenticationSuccessEvent
* LoginSuccessEvent
* LoginFailureEvent
* InteractiveLoginEvent
* LogoutEvent
* TokenDeauthenticatedEvent
* SwitchUserEvent

## Access Control

### Matching Options

* path
* ip/ips
* port
* host
* methods
* request_matcher
* attributes
* route

### Enforcement Options

* roles
* allow_if
* requires_channel
