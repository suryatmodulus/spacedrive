# Spacedrive
<!-- Spacedrive is a cross-platform file manager that brings the convenience of the cloud to your own private network. Designed specifically for independent creatives. -->

Spacedrive is a privacy-first, open source, virtual filesystem powered by your devices combined. The benefits of the cloud but owned and controlled by you and your network of devices. Through a single beautifully designed cross platform interface, you can build a limitless directory of your entire digital life that will stand the test of time.

Out of the box support for photos, movies, albums, audio, VODs, code repositories, social media backups, NFTs, screenshots, saved web pages, links and notes.

## Features
- **File indexing** - Scan your devices, drives, removable storage and cloud accounts to build a virtual "yellow pages" directory of all your data.
- **Realtime synchronization** - sync data between devices securely in realtime.
- **Photos** - Beautiful photo and video albums similar to Apple/Google photos.
- **Search** - Search your entire index at the press of a keybind, including offline devices, drives and clouds.
- **Cloud integration** - Apple Photos, Google Drive, Dropbox, OneDrive & Mega + easy API for the community to add more.
- **Encrypted vault(s)** - Effortlessly manage & encrypt sensitive files, built on top of VeraCrypt. Encrypt individual files or create flexible-size vaults.
- **Key manager** - View, mount, dismount and hide keys. Mounted keys automatically unlock respective areas of your filesystem.
- **Smart tags** - Define routines on tags to automate workflows.
- **Spaces** - A collection of files organized visually and shareable as public web pages with a Spacedrive account.
- **Statistics** - View statistics such as total capacity, index size, preview media size, free space—to name a few.
- **Timeline** - View a linear timeline of content, travel to any time and see media represented visually, including overlapping content.
- **Extensions** - Build tools on top of Spacedrive, extend functionality and integrate third party services. Extension directory on [spacedrive.co/extensions](#).
- **Manage redundancy** - Ensure a specific amount of copies exist for your important data, discover at-risk files and monitor device/drive health.
- **Media encoder** - Encode video and audio into various formats, use Tags to automate.
- **Self host** - Spacedrive can be deployed as a service, behaving as just another device powering your personal cloud.
- **Spacedrive Cloud** - We'll host an always-on cloud device for you, with pay-as-you-go plans for storage.

## Motivation
With a cultural boom of independent creatives there is a lack of tools to support the ever increasing amount of data accumulated. Cloud services have great features, but require your content to be *in* the cloud to benefit from them. For most creators a 50GB OBS recording is just not convenient to upload. 

I believe, in the advent of web3, we need to control and own our own data portfolios, not cloud companies. One uniform way to track, organize, back-up, share, encrypt and view an unlimited amount of data, not locking into a single provider and living within their limits. 

## Architecture
Spacedrive's core is written in pure Rust, with a web based Typescript React UI and native binaries to support additional functionality per platform.

## Apps
- `desktop`: a [Tauri](https://nextjs.org) app
- `mobile`: a [React Native](https://nextjs.org) app
- `web`: another [Next.js](https://nextjs.org) app
- `docs`: a [Next.js](https://nextjs.org) app
  
## Packages
All TypeScript packages are compiled automatically using Turborepo.
- `core`: the [Rust]() core logic library, referred to internally as `sdcorelib`
- `state`: the [TypeScript]() core logic library
- `ui`: a [React Native]() / [RNW]() component library
- `config`: `eslint` configurations (includes `eslint-config-next`, `eslint-config-prettier` and all `tsconfig.json` configs used throughout the monorepo
- `native-macos`: a [Swift]() native binary
- `native-ios`: a [Swift]() native binary
- `native-windows`: a [C#]() native binary
- `native-android`: a [Kotlin]() native binary


## 