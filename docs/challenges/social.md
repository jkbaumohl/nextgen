# Social and User Pages

## Pain points

* No communication between the front-end and the auth (AA) services after login. So, new information is not propagated correctly
* Communicating the state within the UI is not done across webpages. State is held inside a given webpage, but users can have multiple copies (e.g. search uses localStorage). Need a mechanism for _all_ views to discover changes in shared state
* Dashboard performance -- loading is slow due to need to get information from multiple services. The rendering itself is fast enough

## Capabilities

* Dashboard personalization or extension is currently not possible by ordinary users. *Note*: it's _not_ clear that this capability is important to users.
