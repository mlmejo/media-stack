# Homelab Media Stack

Installation steps:
1. Install Docker & Docker Compose.
2. Clone this repo.
3. Create a `.env` file with `MEDIA_PATH=/mnt/media` (or `/Volumes/Media`).
4. Create the folder structure (`mkdir -p ${MEDIA_PATH}/data/torrents` etc.).
5. Run `docker-compose up -d`.
