# fraudulent-assets

This repository contains a list of domains related to suspicious assets on the Stellar network. Each domain in the list is connected to one or several assets related to fraudulent activity, as reported by our users or community members. 

Please refer to [domain-list.txt](domain-list.txt) for a full list of the flagged domains. All assets issued under domains from this document were blacklisted in LOBSTR to protect and warn users before interacting with them.

Every line in the file contains a specific domain name (such as example.com or assets.example.com) or a wildcard domain record (such as `*.example.com`). 

Wildcard records identify multiple sub-domains of a domain. For example, addition of `*.example.com` would blacklist all possible sub-domains of example.com, such as xyz.example.com, abc.example.com or assets.abc.example.com as well as example.com itself.

We are looking to actively expand the list as we are notified about suspicious activity. Please feel free to suggest additions to the list by creating an issue, specifying reasons for inclusion of a specific domain.
