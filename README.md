# BridgeSync for KOReader

BridgeSync is the KOReader plugin for [BookBridge](https://github.com/cporcellijr/bookbridge),
a self-hosted server that keeps reading progress in step across KOReader,
Audiobookshelf, Storyteller, BookOrbit and other readers.

**BridgeSync needs a BookBridge server.** On its own it does nothing.

With a BookBridge server it:

- downloads the books you map in BookBridge to the device and keeps them current
- uploads reading sessions, statistics, reading status and highlights

Your reading position syncs through KOReader's own progress sync pointed at the
same BookBridge server; BridgeSync isn't needed for that.

## Install

- **From a plugin store:** find **BridgeSync** in a KOReader plugin store such as
  [Storefront](https://github.com/ultimatejimmy/storefront.koplugin) and install it.
- **By hand:** download `bridgesync-<version>.zip` from the
  [latest release](../../releases/latest) and unzip it into KOReader's `plugins`
  folder, so you get `plugins/bridgesync.koplugin`.

Restart KOReader, then open **Bridge Sync** in the tools menu and enter your
BookBridge server address and login. Once installed, BridgeSync also offers its
own updates from your BookBridge server.

## Where to report problems

This repository is published automatically from BookBridge's
[`plugins/bridgesync.koplugin`](https://github.com/cporcellijr/bookbridge/tree/main/plugins/bridgesync.koplugin)
on each stable BookBridge release. Please open issues and pull requests in
[cporcellijr/bookbridge](https://github.com/cporcellijr/bookbridge).
