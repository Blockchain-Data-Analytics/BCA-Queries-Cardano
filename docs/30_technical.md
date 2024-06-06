￪ [bach to main](00_main.md)


# Technical information

## Docker setup

![BCA Queries Docker setup](docs/images/BCA%20Queries%20Docker%20images%20setup.png)

We use `docker-compose` to create a convenient setup that works on all major platforms. 

The connection between your machine and our servers is protected by an encrypted VPN. On our end we run a proxy in front of high-availability databases. The proxy listens on port 25432 and forwards to the PostgreSQL servers. It would also do failover in case one of the databases is offline.

At the other end of the VPN connection in your machine this port 25432 is forwarded to internally 35432 and then exposed on your machine as port 5432 (this can be [changed](31_port_change.md)).

The tool _pgAdmin_ can be accessed on http://localhost:5480. For its usage see [pgAdmin](10_use_pgadmin.md).
