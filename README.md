xcode-i18n
==========

Internationalization scripts working with xcode

## What does it do?
It provides incremental localization on XCode projects, including text strings, XIB and storyboard files.

## How to use?
Fill in Localizable.strings as you always do, but including text strings (for code using NSLocalizedString), XIB and storyboard files.

Set up your XIBs/Storyboards in English language, provide translations in Localizable.strings and have this script create/update localized XIBs/Storyboards for you.

Add it as build phase in Xcode or run manually every time you need.
