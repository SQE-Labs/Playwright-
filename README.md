## Introduction

Playwright Test was created specifically to accommodate the needs of end-to-end testing. Playwright supports all 
modern rendering engines including Chromium,WebKit, and Firefox. Test on Windows, Linux, and macOS, locally or on 
CI, headless or headed with native mobile emulation of Google Chrome for Android and Mobile Safari.

## System requirements

Node.js 18+
Windows 10+, Windows Server 2016+ or Windows Subsystem for Linux (WSL).
macOS 13 Ventura, or macOS 14 Sonoma.
Debian 11, Debian 12, Ubuntu 20.04 or Ubuntu 22.04, Ubuntu 24.04, on x86-64 and arm64 architecture.

## Installation 

npm install playwright@latest

## Run 

npx playwright test

## Show HTML Report

npx playwright show-report


## Run in UI mode

npx playwright test --ui

# Commands 
npx playwright test grouping.spec.ts --project=chromium --headed


