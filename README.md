# Private, encrypted, and secure DNS

Yet another ad/tracker/malware-blocking [no-logs free public DNS](https://dns.repinger.my.id).


## DNS over TLS (DoT)
Port 853/tcp

### Usage
```
tls://dns.repinger.my.id / dns.repinger.my.id
```

### IPv4 stamp
```
sdns://AwIAAAAAAAAADzIwMy4xOTQuMTEyLjIyOCBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhJkbnMucmVwaW5nZXIubXkuaWQ
```

### IPv6 stamp
```
sdns://AwIAAAAAAAAAE1syMDAxOmRmMDoyN2I6OjI0MF0gRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984SZG5zLnJlcGluZ2VyLm15Lmlk
```

## DNS over HTTPS (DoH)
Port 443/tcp

### Usage
```
https://dns.repinger.my.id/dns-query
```

### IPv4 stamp
```
sdns://AgIAAAAAAAAADzIwMy4xOTQuMTEyLjIyOCBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhJkbnMucmVwaW5nZXIubXkuaWQKL2Rucy1xdWVyeQ
```

### IPv6 stamp
```
sdns://AgIAAAAAAAAAE1syMDAxOmRmMDoyN2I6OjI0MF0gRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984SZG5zLnJlcGluZ2VyLm15LmlkCi9kbnMtcXVlcnk
```

## DNS over QUIC (DoQ)
Port 853/udp

### Usage
```
quic://dns.repinger.my.id
```

### IPv4 stamp
```
sdns://BAIAAAAAAAAAEzIwMy4xOTQuMTEyLjIyODo4NTMgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984SZG5zLnJlcGluZ2VyLm15Lmlk
```

### IPv6 stamp
```
sdns://BAIAAAAAAAAAF1syMDAxOmRmMDoyN2I6OjI0MF06ODUzIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOEmRucy5yZXBpbmdlci5teS5pZA
```
