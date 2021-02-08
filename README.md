# systemd.rs

[![buy me a coffee](https://img.shields.io/badge/buy%20me%20a%20coffee-or%20I%20sing-53a0d0?style=flat&logo=Buy-Me-A-Coffee)](https://www.buymeacoffee.com/ente)  [![donate@paypal](https://img.shields.io/badge/paypal-donation-53a0d0?style=flat&logo=paypal)](https://www.paypal.com/donate?hosted_button_id=CRGNTJBS4AD4G)

[systemd.rs](https:://github.com/ente76/systemd.rs) is a group of packages that define rust wrappers for certain functionality in libsystemd:

github.com | crates.io | docs.rs
-----------|-----------|--------
[sd-sys](https://github.com/ente76/sd-sys) | [![Crates.io](https://img.shields.io/crates/v/sd-sys)](https://crates.io/crates/sd-sys) | [![docs.rs](https://docs.rs/sd-sys/badge.svg)](https://docs.rs/sd-sys/)
[sd-id128](https://github.com/ente76/sd-id128) | [![Crates.io](https://img.shields.io/crates/v/sd-id128)](https://crates.io/crates/sd-id128) | [![docs.rs](https://docs.rs/sd-id128/badge.svg)](https://docs.rs/sd-id128/)
[sd-journal](https://github.com/ente76/sd-journal) | [![Crates.io](https://img.shields.io/crates/v/sd-journal)](https://crates.io/crates/sd-journal) | [![docs.rs](https://docs.rs/sd-journal/badge.svg)](https://docs.rs/sd-journal)

systemd.rs is an alternative to the [systemd-rust](https://github.com/jmesmon/rust-systemd) project.

- systemd.rs is published under the AGPL-3.0 license. Individual/commercial licenses are available upon request.
- focused coverage of sd-id128 & sd-journal only (currently there are no plans to extend this coverage)
- good documentation with links to the libsystemd documentation
- 100% coverage of libsystemd within the area of focus
- good test coverage
- focus on usability

## License

sd-sys is published under the AGPL-3.0, individual licenses may be granted upon request.

```license
sd-sys: FFI bindings to systemd for sd-id128 & sd-journal
Copyright (C) 2020 Christian Klaue [mail@ck76.de]

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
