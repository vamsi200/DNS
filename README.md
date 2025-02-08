# DNS server from scratch  

This repository is a follow-through of [Emil Hernvall's DNS guide](https://github.com/EmilHernvall/dnsguide.git).  
I'm implementing the steps from the guide to deepen my understanding of network programming.  

## What This Project Does  
- Uses **UDP sockets** to send and receive DNS queries.  
- Parses DNS responses and extracts meaningful data.  

## How to Run  
Ensure you have Rust installed. Then, clone the repository and run:  

```sh
cargo build --release
cargo run
```
- Starts a Udpserver on port `2053`

```sh 
dig @127.0.0.1 -p 2053 google.com
```
