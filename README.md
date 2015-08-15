# libvideo

[![Join the chat at https://gitter.im/James-Ko/libvideo](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/James-Ko/libvideo?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

libvideo is a .NET library that provides a fast, succinct way to download YouTube videos. It has **NO** external dependencies, and full support for both async and synchronous callers.

libvideo runs about 25% to 75% faster than the main alternative, [YoutubeExtractor](https://github.com/flagbug/YoutubeExtractor). This is mainly due to its substitution of optimized string code in place of YoutubeExtractor's use of full-fledged JSON and query parsers; libvideo also avoids regex for simple string operations.

## [On NuGet](https://www.nuget.org/packages/VideoLibrary)
To install libvideo, you can run the following command in the Package Manager Console:

    Install-Package VideoLibrary

## Usage

See the [docs](docs/README.md) for instructions.

## Supported Platforms

libvideo supports the following platforms:

- .NET Framework 4.5+
- Windows 10 Universal apps
- Portable Class Libraries
- Windows 8.1 and 8.0
- Windows Phone 8.1 (WinRT)

## Donations

libvideo does not accept donations, but please [help out](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=daume%2edennis%40gmail%2ecom&lc=US&item_name=YoutubeExtractor&no_note=0&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHostedGuest) the creator of the original library, YoutubeExtractor. His project was an essential part in creating libvideo, and I don't want to cut off his funds.
