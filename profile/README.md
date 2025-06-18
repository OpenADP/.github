# OpenADP

Open source Advanced Data Protection for everyone

This project is recruiting!  Consider helping out!
Either [post on Issue #1](https://github.com/OpenADP/openadp/issues/1), or
[join us on Discord](https://discord.gg/TaHNeGsE8j)

## Motivation

Today, systems like Apple's Advanced Data Protection [are under
attack](https://www.bloomberg.com/news/articles/2025-02-21/apple-removes-end-to-end-encryption-feature-from-uk-after-backdoor-order).
There is a real threat that governments will order creation of secret mass
surveillance backdoors like [what Yahoo was forced to
build](https://www.reuters.com/article/technology/yahoo-secretly-scanned-customer-emails-for-us-intelligence-sources-idUSKCN1241YV/).
Existing systems defend backups from warrants, but there is no transparency,
and no way for the public to know if the system has been compromised.

This is where OpenADP comes in.  All code will be 100% open source, and rather
than relying on proprietary HSMs (Hardware Security Modules), we'll use
distributed trust.  Users don't have to trust any particular OpenADP operator,
just that a threshold of them are honest.

When turned up, the whole world will be able to securely encrypt their data for
free, protecting backups, passwords, message history, and more, if we can get
existing applications to use to the new data protection service.

## Volunteering

We need help, so please consider volunteering!  We know how to build the
server, which won't be much work.  However, we'll need folks to run the server
to provide the distributed trust network.  Areas where we need help include:

* Running OpenADP servers. This is a T-of-N scheme, where users will need
  say 9 of 15 nodes to be available to recover their backups.
* Android client app, and preferably tight integration with the platform as an
  alternate backup service.
* Same with iOS
* Authentication. Users should register, and login before they can use any of
  their limited guesses to their phone unlock secret.
