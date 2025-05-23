# Local Development Setup

This document explains how to set up local development for this Ghost theme.

## Prerequisites
- Node.js 20.x (managed by Volta)
- Yarn
- Ghost CLI

## Local Development

1. Clone this repository
2. Install dependencies: `yarn install`
3. Start theme development: `yarn dev`

## Local Ghost Testing

1. Create a `local-dev` directory (ignored by Git)
2. Install Ghost locally: `ghost install local`
3. Copy theme files to Ghost themes directory
4. Import production data for testing

## Theme Deployment

This repository contains only the theme files needed for production deployment.
Upload the entire repository contents to your Ghost site's themes directory.

## Files Ignored by Git

- `local-*/` - Local Ghost installations
- `node_modules/` - Dependencies
- `*.sh` - Development scripts
- `*.ghost.*.json` - Ghost export files
