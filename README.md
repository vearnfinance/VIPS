# VIPs [![Discord](https://img.shields.io/discord/734804446353031319.svg?color=768AD4&label=discord&logo=https%3A%2F%2Fdiscordapp.com%2Fassets%2F8c9701b98ad4372b58f13fd9f65f966e.svg)](https://discordapp.com/channels/????/) [![Telegram](https://img.shields.io/badge/chat-on%20Telegram-blue.svg)](https://t.me/vearnfinance) [![Twitter Follow](https://img.shields.io/twitter/follow/vearnfinance.svg?label=vearnfinance&style=social)](https://twitter.com/vearnfinance)

vEarn Improvement Proposals (VIPs) describe standards for the vEarn platform, including core protocol specifications, client APIs, and contract standards.
 
## Contributing

 1. Review [VIP-0](VIPS/vip-0.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your VIP to your fork of the repository. There is a [template VIP here](vip-X.md).
 4. Submit a Pull Request to vEarn's [VIPs repository](https://github.com/vearnfinance/VIPS/).

Your first PR should be a first draft of the final VIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new VIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a new thread on [gov.vearn.finance](https://gov.vearn.finance/) where people can discuss the VIP as a whole.

If your VIP requires images, the image files should be included in a subdirectory of the `assets` folder for that VIP as follow: `assets/vip-X` (for vip **X**). When linking to an image in the VIP, use relative links such as `../assets/vip-X/image.png`.

When you believe your VIP is mature and ready to progress past the WIP phase, you should ask to have your issue added to the next governance call where it can be discussed for inclusion in a future platform upgrade. If the community agrees to include it, the VIP editors will update the state of your VIP to 'Approved'.

## VIP Statuses

* **WIP** - a VIP that is still being developed.
* **Proposed** - a VIP that is ready to be reviewed in a governance call.
* **Approved** - a VIP that has been accepted for implementation by the yEarn community.
* **Implemented** - a VIP that has been released to mainnet.
* **Rejected** - a VIP that has been rejected.
* **Withdrawn** - a VIP that has been withdrawn by the author(s).
* **Deferred** - a VIP that is pending another VIP/some other change that should be bundled with it together.
* **Moribund** - a VIP that was implemented but is now obsolete and requires no explicit replacement.

## Validation

VIPs must pass some validation tests.  The VIP repository ensures this by running tests using [html-proofer](https://rubygems.org/gems/html-proofer) and [vip_validator](https://rubygems.org/gems/vip_validator).

It is possible to run the VIP validator locally:
```
gem install vip_validator
vip_validator <INPUT_FILES>
```

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
