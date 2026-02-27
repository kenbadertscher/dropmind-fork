# DropMind

> If it lives in your head, it should live on your server.

DropMind is a self-hosted memory cache for your digital thoughts.

Save links, notes, files, images and locations in one place --- fully
under your control.

No cloud lock-in. No external accounts. Just your server.

------------------------------------------------------------------------

## ✨ Features

-   📌 Pin important messages
-   📎 File & image upload
-   🔗 Smart link cards
-   📍 Map / GPS location detection
-   🗂 Multiple clipboards
-   ⭐ Favorite clipboard
-   🔍 Local & global search
-   🌙 Clean dark UI
-   📱 Fully mobile responsive
-   🐳 Docker-ready backend

------------------------------------------------------------------------

## 📸 Interface Preview

### Desktop

![Desktop UI](docs/desktop.png)

### Mobile

![Mobile UI](docs/mobile.png)

------------------------------------------------------------------------

## 🧠 Philosophy

DropMind was born from a simple idea:

Your thoughts are personal.\
Your memory system should be too.

This is not a cloud service.\
It is a self-hosted digital extension of your mind.

------------------------------------------------------------------------

## 🏗 Architecture

-   Backend: FastAPI\
-   Database: SQLite\
-   Frontend: Vanilla HTML / CSS / JS\
-   Containerized: Docker

Designed to be lightweight, portable and easy to deploy on:

-   Raspberry Pi
-   Home server
-   VPS
-   NAS

------------------------------------------------------------------------

## 🚀 Installation (Docker)

``` bash
git clone https://github.com/YOUR_USERNAME/dropmind.git
cd dropmind
docker compose up -d
```

Then open:

    http://localhost:8000

------------------------------------------------------------------------

## ⚙ Configuration

Create a `config.js` file in the frontend root:

``` js
window.DM_CONFIG = {
  API_TOKEN: "your-secure-token"
};
```

Set the same token in backend environment variables.

------------------------------------------------------------------------

## Why AGPL?

To ensure that DropMind remains open if modified and offered as a public
service.

------------------------------------------------------------------------

## 📜 License

DropMind is licensed under the GNU Affero General Public License v3.0
(AGPL-3.0).

You are free to use, modify and self-host it.

If you modify DropMind and deploy it publicly, you must release your
changes under the same license.

------------------------------------------------------------------------

## 🌊 Drop it. Own it. Move on.
