> [!IMPORTANT]  
> As of 27/03/25, inko-dns has been discontinued.
>
> DNS resolver support is now available in Inko's standard library
>
> For more information refer to [inko docs / std.net.dns](https://docs.inko-lang.org/std/main/module/std/net/dns/)

# Inko DNS

DNS Client written in the [Inko programming language](https://inko-lang.org/)

## Examples

```rs
import dns(DNSResolver)

let address = DNSResolver.new.resolve("www.google.com").address
```

`address` is an `IpAddress`
