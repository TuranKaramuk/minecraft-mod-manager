# Minecraft Mod Manager

A security-focused, non-commercial Minecraft mod management tool for private home servers.

## Overview

Minecraft Mod Manager is a Python and FastAPI application for discovering, reviewing, and managing Minecraft mods.

The project currently supports:

- Local inventory scanning of installed Minecraft mods
- Modrinth version and update checking
- Minecraft and NeoForge compatibility filtering
- Mod metadata and dependency inspection
- Verified downloads into an isolated staging directory

CurseForge API integration is under development and pending API authorization.

## Security

The application is designed for private, self-hosted environments.

- Web administration is accessible only through an SSH tunnel.
- No public administration ports are required.
- The application does not expose the Docker socket.
- Mod installation and updates require explicit user approval in the planned deployment workflow.
- API credentials are never committed to the repository.

## Project Status

**Active development — V3.1.2**

The application currently provides read-only inventory and update discovery, with staging support for compatible Modrinth files.

Automated installation, rollback, and additional CurseForge integration are planned.

## Technology

Python, FastAPI, HTML, JavaScript, SQLite (planned).

## Usage

Personal, non-commercial home server management.
