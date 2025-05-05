# AIT Rapid Deployment Platform

## Overview

![Overview of RDP Components](./img/ait-rdp-overview.svg "Overview of RDP components")

## RDP Components

| | |
|------|--------------------------|
| ![Logo RDP Database](./img/pyrdp-commons.png "Logo") | [RDP Database](https://ait-rdp.github.io/rdp-database): Hosts the scheme as well as the migration scripts that set up the long-term storage based on Timescale DB |
| ![Logo RedSQL Data Sync](./img/rdp-database.png "Logo") | [RedSQL Data Sync](https://ait-rdp.github.io/rdp-redsql): Generic Redis to SQL data synchronizer |
| ![Logo PyRDP Commons](./img/redsql.png "Logo") | [PyRDP Commons](https://ait-rdp.github.io/pyrdp-commons): A small helper library to group common AIT RDP functions and to provide a unified user experience |
| ![Logo RDP Data Crawler](./img/data-crawler.png "Logo") | [RDP Data Crawler](https://ait-rdp.github.io/rdp-data-crawler): Periodically fetches publicly available forecast and measurement information and stores it into Redis streams |
| ![Logo Modbus Crawler](./img/modbus-crawler.png "Logo") | [Modbus Crawler](https://ait-rdp.github.io/rdp-modbus-crawler): Simple Python Modbus Crawler that reads registers of a Modbus server/slave based on a register secification in a data frame/csv/... |
