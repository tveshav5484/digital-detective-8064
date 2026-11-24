# Mission 7 - Networks

## Task 7.1 - Networking Concepts

| Term | Meaning |
|---|---|
| LAN | A network connecting devices in a small area, such as a home or college |
| MAN | A network covering a city or larger urban area |
| WAN | A network connecting devices or networks over large distances |
| DNS | Converts domain names into IP addresses |
| Router | Directs network traffic between networks |
| Protocol | A set of rules used for communication between devices |
| Packet switching | Data is divided into packets that travel across networks |
| Client-server | A system where a client requests information or services from a server |

## Task 7.2 - Network Testing

I used the ping command to test connectivity to a public website.

```bash
ping -c 4 google.com
```

I also used nslookup to perform a DNS lookup.

```bash
nslookup google.com
```

The ping command tests connectivity by sending packets and receiving responses. The nslookup command helps find the IP address associated with a domain name.

## Task 7.3 - What Happens When Visiting a Website?

1. I enter a website address into my browser.
2. DNS translates the domain name into an IP address.
3. My device sends a request through the network and router.
4. The request reaches the website's server.
5. The server sends the requested information back.
6. The browser processes the response and displays the website.

## Learning

I learned the basic concepts of networking, including LAN, MAN, WAN, DNS, routers, protocols, packet switching and client-server communication. I also practised testing connectivity and performing DNS lookups using Terminal.
