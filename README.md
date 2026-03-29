# Blackout VPN for iOS & macOS

This is the official iOS and macOS client for **Blackout VPN**, a lightweight, private, no-logs VPN powered by modern WireGuard tunnels.  
No analytics. No tracking. Just a fast encrypted tunnel.

## Building

- Clone this repo:
```
$ git clone https://github.com/blackoutvpn/blackout-apple
$ cd blackout-apple
```

- Rename and populate developer team ID file:
```
$ cp Sources/WireGuardApp/Config/Developer.xcconfig.template Sources/WireGuardApp/Config/Developer.xcconfig
$ vim Sources/WireGuardApp/Config/Developer.xcconfig
```

- Install swiftlint and go:
```
$ brew install swiftlint go
```

- Open project in Xcode:
```
$ open WireGuard.xcodeproj
```

- Select the iOS or macOS target and build.

## Notes

Blackout VPN does not collect logs, analytics, crash reports, or any user-identifying data.  
Both iOS and macOS targets are contained in this repository and share common components.

## License

MIT License. This project is modified from [wireguard-apple](https://git.zx2c4.com/wireguard-apple) by WireGuard LLC.  
Copyright (C) 2018-2022 WireGuard LLC. All Rights Reserved.
