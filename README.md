# Skautik SDK for Python

Client for the Skautik partner API: property data, market analytics, imports, exports, enquiries, and webhooks.

## Install

```
pip install skautik-sdk
```

## Documentation

The API reference, guides, and examples live at
https://skautik.com/developers/docs, and in
[skautikhq/skautik-docs](https://github.com/skautikhq/skautik-docs).

You will need an API key from the developer console. Keys carry a fixed set of
scopes, and a call whose key lacks the scope its endpoint requires is refused
rather than partly served.

## This repository is generated

Every file here is generated from Skautik's OpenAPI description, which the API
emits from its own route tree. A test in the API fails if that description and
the router disagree, which is what makes this client trustworthy without
anybody checking it by hand.

**Do not send pull requests here.** They cannot be merged: the next release
overwrites this repository entirely, without a conflict to notice.

- A wrong or missing endpoint is a bug in the API's description.
- A problem with how this client is shaped is a bug in the generator.

Report either at [skautikhq/skautik-sdk](https://github.com/skautikhq/skautik-sdk/issues),
which is where the fix goes.

## Licence

MIT. See [LICENSE](LICENSE).
