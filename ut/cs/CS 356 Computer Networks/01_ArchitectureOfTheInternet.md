# Architecture of the Internet
![hopping](images/a.png)

- Max # of hops: 64
- **TTL**: Time To Live (until a msg dies)
    - How to ensure message doesn't just fizzle out unknown? TTL is set to 64 by default

**Types of Computers**

| Name | Picture |
| --- | --- |
| Router | ![hopping](images/b.png) |
| Client Host | ![hopping](images/c.png) |
| Server Host | ![hopping](images/d.png) |

The lines underneath are subnetworks.

- Routers have multiple subnetworks
- Server host & client host have 1 subnetwork

Types of subnetwork technologies:

- LANs (switched ethernets)
- Wireless LANs
- Phone lines
- TV cables
- Satellite links

Wireless device to a wifi client host = 1 hop

To navigate from 1 network to another, you must go through ISPs