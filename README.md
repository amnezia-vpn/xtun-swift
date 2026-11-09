This is the SPM repository stores Swift bindings for xtun library.


Use this code within your Package.swift to use this dependency
```
dependencies: [
    .package(url: "https://github.com/amnezia-vpn/xtun-swift", from: "0.1.0"),
],
targets: [
    .target(name: "MyTunnel", dependencies: [
        .product(name: "Xtun", package: "xtun-swift"),
    ]),
]
```
