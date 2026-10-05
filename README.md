# Cirethic Connector

Installer downloads for the **Cirethic Connector**: the small local program that
lets the Cirethic operator app (app.cirethic.com) use a pro DSLR camera and a
label printer. Browsers cannot talk to that hardware directly; the Connector
bridges it to your browser tab.

**This repository holds releases only. No source code lives here.**

## Download

Get the newest build from [Releases](../../releases/latest), or download it from
inside Cirethic on the Hardware page. That button points here.

## What it is

It is a cable, not a service. The Connector runs only on your computer and talks
only to your Cirethic tab at app.cirethic.com. Your photos go straight from the
camera into Cirethic; they never travel anywhere through the Connector, and it
stops when you close its window.

## Requirements

- Windows
- [digiCamControl](https://digicamcontrol.com/) installed, with its webserver
  enabled on port 5513. The Connector drives the camera through it.

## A note on the Windows warning

The binary is **not code-signed yet**, so Windows SmartScreen will warn about an
unknown publisher the first time you run it. That is the missing signature, not
a problem with the file. Only trust a copy downloaded from inside Cirethic or
from this releases page, never one sent by email or hosted elsewhere.

Cirethic AB · org.nr 559604-7299
