# DNS Resolver in Rust  

This repository is a follow-through of [Emil Hernvall's DNS guide](https://github.com/EmilHernvall/dnsguide.git).  
I'm implementing the steps from the guide while adding my own notes, modifications, and experiments to deepen my understanding of Rust network programming.  

## What This Project Does  
- A simple **DNS resolver** built from scratch in Rust.  
- Uses **UDP sockets** to send and receive DNS queries.  
- Parses DNS responses and extracts meaningful data.  

## How to Run  
Ensure you have Rust installed. Then, clone the repository and run:  

```sh
cargo build --release
cargo run -- <domain-name>

