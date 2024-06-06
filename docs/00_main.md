# Cardano Queries

![Cardano Queries icon](images/BCA_Queries_256x256.png)

## Content

- [Signup to this service](#signup-for-this-service)
- [Data source](#data-source)
- [Setup Cardano Queries on your machine](#setup-cardano-queries-on-your-machine)
- [How to run queries through this service](#how-to-run-queries-through-this-service)

![   ](images/vspace.png)

## Signup for this service

> for a limited time during the beta-phase of this project until end of August 2024 we provide a **50% reduction** on the subscription fee

Depending on your location you may choose to connect to either:

[![Banner Cardano Queries EU](images/BCA%20Queries%20banner%20EU.png)](https://github.com/sponsors/Blockchain-Data-Analytics/sponsorships?pay_prorated=true&tier_id=406906)
[![Banner Cardano Queries US](images/BCA%20Queries%20banner%20US.png)](https://github.com/sponsors/Blockchain-Data-Analytics/sponsorships?pay_prorated=true&tier_id=406907)

| location | sponsorship tier | link |
|----|----|----|
| Europe 🇪🇺 |  $29 per month  | [select EU servers](https://github.com/sponsors/Blockchain-Data-Analytics/sponsorships?pay_prorated=true&tier_id=406906) |
| North America 🇺🇸  | $28 per month | [select US servers](https://github.com/sponsors/Blockchain-Data-Analytics/sponsorships?pay_prorated=true&tier_id=406907) |

Payment of the selected sponsorship gives you the right to use the service for up to a month. Renewal of the sponsorship extends the service period. And, cancellation of your sponsorship will also terminate the service at the end of the paid period. Please understand that we cannot reimburse you.

We cannot provide you with a strict SLA. But, we promise to keep the services alive and fix technical problems asap. We have decent monitoring in place and will be able to react to service disruption.

See our [main page](https://github.com/Blockchain-Data-Analytics) for contact details.

![   ](images/vspace.png)

## Data source

The data is derived using [Db-sync](https://github.com/IntersectMBO/cardano-db-sync) from Cardano's main chain.

We provide you with a complete setup containing all credentials to connect to our high-availability PostgreSQL servers.

Prerequisites: you need to have [Docker](https://www.docker.com/products/docker-desktop/) installed.

![   ](images/vspace.png)

## Setup Cardano Queries on your machine

### Windows ![Windows](images/win.png)

[Windows setup](01_setup_win.md)

### macOS ![macOS](images/mac.png)

[macOS setup](02_setup_mac.md)

### Linux ![Linux](images/linux.png)

[Linux setup](03_setup_linux.md)

### on other operating systems

e.g. FreeBSD

[other setup](04_setup_other.md)

![   ](images/vspace.png)

## How to run queries through this service

### Running queries in _pgAdmin_

[using pgAdmin](10_use_pgadmin.md)

### Sending queries directly to PostgreSQL

[PostgreSQL connection](20_direct_pg.md)
