# VeilChat

**Private rooms. No accounts. Your link.**

VeilChat is an experimental self-hosted private chat prototype. It lets you start a tiny local chat server, create a temporary public link, and invite someone with a simple room code.

No accounts. No database. No stored chat history.

> **Status:** alpha prototype  
> **Use for:** testing, learning, demos, private experiments  
> **Do not use for:** high-risk or security-critical communication

---

## What is VeilChat?

VeilChat is a small self-hosted chat app designed around a simple idea:

1. One person starts VeilChat.
2. VeilChat creates a temporary public link.
3. The host sends that link to a friend.
4. The host creates a room code like `BLUE-FOX-42`.
5. The friend enters the code.
6. Chat starts.

VeilChat is built to be easy to test with normal users while avoiding accounts, signups, databases, and paid hosting.

---

## Features

- **Room Codes**  
  Connect with short codes like `BLUE-FOX-42`.

- **Temporary Public Links**  
  Uses Cloudflare Quick Tunnel to create a temporary public `trycloudflare.com` link.

- **No Accounts**  
  No email, username, phone number, or signup flow.

- **No Database**  
  Rooms exist only in memory while the server is running.

- **No Stored Chat History**  
  Refreshing or stopping the server clears chat state.

- **Relay Privacy Mode**  
  Optional fallback mode where messages are encrypted in the browser and relayed through the host server instead of using direct peer-to-peer WebRTC.

- **Full-Screen Chat View**  
  A clean chat-only view for a better conversation experience.

- **Windows and macOS Starters**  
  Simple double-click start scripts for non-technical testers.

---

## Quick Start

Download the latest release ZIP and choose your platform folder.

### Windows

Double-click:

```text
START VEILCHAT.bat
