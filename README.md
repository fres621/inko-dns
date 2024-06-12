# Inko DNS
DNS Client written in the [Inko programming language](https://inko-lang.org/)

## Examples
```rs
import dns(DNSResolver)

let address = DNSResolver.new.resolve("www.google.com").address
```
`address` is an `IpAddress`