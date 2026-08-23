**[EN](README.md) | [RU](README.ru.md)**

This repository contains up-to-date server lists for the **LSB (Launcher & Server Browser)** program, designed for Counter-Strike 1.6.

It serves as a centralized data source, allowing LSB clients to always have access to a fresh list of game servers without manual updates.

## Repository Contents

The repository includes two main text files:

### ms.txt

This is the primary file with the server list. It contains addresses of active Counter-Strike 1.6 game servers in the format IP:Port.

- **Purpose:** Used by LSB clients to populate the "Internet" tab with current servers.
- **Updates:** The file is regularly updated to add new servers and remove non-functional ones.

### blacklist.txt

This file contains a list of servers that have been excluded from the main list.

- **Purpose:** Serves to filter out undesirable, unstable, fake servers, those without FastDL, as well as mirror servers. This improves the quality of the main list provided in `ms.txt`.
- **Updates:** The file is updated after reviewing Issue or Pull Request requests, as well as complaints from the ONGG community.

## How to Contribute

This repository is maintained by the community to ensure the server lists remain current. If you want to suggest changes (e.g., add a new popular server or report a non-working one), you can open an Issue or Pull Request in this repository.

## Relation to LSB

This server list is designed for use with the **Launcher & Server Browser (LSB)** program. For more detailed information about the program itself, its features, and setup, please visit the official project page.
