# Modular Standard Configuration
[![GitHub issues](https://img.shields.io/github/issues/modular/standard)](https://github.com/modular/standard/issues)
[![GitHub license](https://img.shields.io/github/license/modular/standard)](https://github.com/modular/standard/blob/master/LICENSE)
[![GitHub tag](https://img.shields.io/github/tag/modular/standard.svg)](https://github.com/modular/standard/tags)
[![GitHub release](https://img.shields.io/github/release/modular/standard.svg)](https://github.com/modular/standard/releases)

[Modular](https://github.com/modular) |
[Modulo](https://github.com/modulo)

Standard Modular Network Configuration (standard)

Modular is a an open-source standard for decentralized social communication. It aims to solve the issues of censorship, deplatforming, intrusive adveritsing, poor user privacy that are prevalent on centralized social media platforms. Users on a Modular Network can communicate with eachother across the world without any centralized point of failure.

## Download
### GitHub
[Download Latest Release](https://github.com/modular/standard/releases)

### CDN
[JSDelivr Page](https://www.jsdelivr.com/package/npm/@modular/standard)

	<script src="https://cdn.jsdelivr.net/npm/@modular/standard/standard.min.js"></script>

## Installation
### In a browser:
	<script src="standard.min.js"></script>

### Using npm:
	npm i --save @modular/standard

### In Node.js:
	require('@modular/standard').config().then((config) => {
		this.config = config;
	});
