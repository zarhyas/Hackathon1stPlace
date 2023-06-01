# 🏆 OpenSource 11 Hackathon Winner Project

Our proposed solution for the [**OpenSource**](https://opensource.rf.gd/) HackaThon organized at **ENSA khouribga**.

## Team

| [@Yasser Nabouzi](https://github.com/NBGamer99)           | [@Hamza Mesrar](https://github.com/ez7mz)                        | [@Yasser Zarhloul](https://github.com/zarhyas)            |
| --------------------------------------------------------- | ---------------------------------------------------------------- | --------------------------------------------------------- |
| ![](https://avatars.githubusercontent.com/u/80721528?v=4) | ![l3agrab](https://avatars.githubusercontent.com/u/82721617?v=4) | ![](https://avatars.githubusercontent.com/u/74158634?v=4) |

## Problem

The goal was to develop a system that could effectively dispatch available emergency vehicles from nearby depots to the incident location, while also selecting the most optimal route.

The system's design prioritized minimizing response time by considering factors such as distance, and the number of turns along the route.

## Solution

To achieve our goal of minimizing response time, we developed a solution based on the A\* (A-star) and relied on a heuristic that minimizes the distance and number of turns with constraints on the capacity and level of the incident.

## How to run locally

```bash
python3 -m venv env
source ./env/bin/activate

# optional
pip install pip -U
pip install setuptools -U

pip install -r requirements.txt

apt install spatialite-bin
apt install sqlite3 libsqlite3-dev
apt install binutils libproj-dev gdal-bin

sh ./setup-app.sh
```
