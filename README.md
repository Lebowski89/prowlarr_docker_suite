Prowlarr Suite
=========

    Standalone Ansible role to automate the full set-up of Prowlarr - an indexer manager for Usenet and BitTorrent users.
      - Includes the installation of Docker (Debian-based distros) and Ansible dependencies within the role.
      - Includes the option of setting up and connecting Prowlarr to a Postgres database.
      - Includes the option of setting up Prometheus and a Prowlarr Promtheus exporter to gather various metrics about your Prowlarr usage and music collection.
      - Includes the option of creating a Cloudflare DNS record for your Prowlarr instance for reverse proxy purposes.
      - Includes the option of joining Prowlarr to an existing Traefik docker network (or creating one if none exists).
      - Includes the option of editing Prowlarr's config.xml to include an existing Prowlarr API - maintaining connections to other applications that rely on it.

(Proper documentation is coming...)
