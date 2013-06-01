# OAuth 1.0a Provider with Redis in Python

I want to build a scalable OAuth 1.0a Provider that is is to subclass specifically in authenticating users against
various databases. Focuses in leveraging performance by using Redis as the primary OAuth Provider backend, user
authentications can be handled differently using any other databases.

Coded against [RFC5849](http://tools.ietf.org/html/rfc5849) so please excuse any mishaps, everyone is welcomed to fork
and send pull requests.

## Compatibility Against [RFC5849](http://tools.ietf.org/html/rfc5849)

With this README, I have no plans in supporting 3 legged authentications. I am only supporting XAuth at the moment.
Fork and contribute to add support to 3 legged authentications.

OAuth Authorization components are all expected from a HTTP POST body except for OAuth Signatures, this is expected
from query strings.

Will refactor later on, it seems that my REST tool is not supporting extra Authentication headers properly.

## Using

Don't! Not yet.