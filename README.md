# Sails Protocol Documentation

Official technical documentation source for the Sails Protocol, its reference node, SDK integrations, guides and API surface.

- Protocol repository: https://github.com/sails-protocol/Sails-Protocol
- Integration starter: https://github.com/sails-protocol/sails-integration-starter
- Independent P2P safety education: https://github.com/sails-protocol/Sails-P2P-Safety-Center

## Local development

This site uses [Mintlify](https://mintlify.com/docs). Run the Mintlify CLI in the repository root:

```bash
npx mint dev
```

Navigation and site metadata live in `docs.json`; articles are written in MDX.

## Publishing

Production publishing depends on the Mintlify project's GitHub integration. After moving this repository to the `sails-protocol` organization, verify that the Mintlify project points to `sails-protocol/sails-protocol-docs` and has repository access before relying on automatic deployment. Do not assume a GitHub transfer updates the Mintlify connection.

## Scope

Technical implementation documentation belongs here. The Safety Center is a separate educational site; neither replaces the protocol's normative specifications and implementation evidence.
