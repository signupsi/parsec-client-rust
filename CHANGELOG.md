# Changelog

## [0.11.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.11.0) (2020-10-20)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.10.0...0.11.0)

**Implemented enhancements:**

- Implement provider and auth bootstrapping [\#58](https://github.com/parallaxsecond/parsec-client-rust/pull/58) ([ionut-arm](https://github.com/ionut-arm))
- Add Unix Peer Credential auth support [\#57](https://github.com/parallaxsecond/parsec-client-rust/pull/57) ([ionut-arm](https://github.com/ionut-arm))
- Remove filesystem checks [\#56](https://github.com/parallaxsecond/parsec-client-rust/pull/56) ([ionut-arm](https://github.com/ionut-arm))

**Fixed bugs:**

- Socket path security checks can fail when the client is in a container [\#51](https://github.com/parallaxsecond/parsec-client-rust/issues/51)

**Closed issues:**

- Implement new authenticator support [\#41](https://github.com/parallaxsecond/parsec-client-rust/issues/41)

**Merged pull requests:**

- Add a new construction for naked client [\#59](https://github.com/parallaxsecond/parsec-client-rust/pull/59) ([hug-dev](https://github.com/hug-dev))
- Quickfix: replace parsec-interface patch with a direct dependency [\#54](https://github.com/parallaxsecond/parsec-client-rust/pull/54) ([joechrisellis](https://github.com/joechrisellis))
- Add ListKeys support [\#53](https://github.com/parallaxsecond/parsec-client-rust/pull/53) ([joechrisellis](https://github.com/joechrisellis))

## [0.10.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.10.0) (2020-10-02)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.9.0...0.10.0)

## [0.9.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.9.0) (2020-09-07)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.8.0...0.9.0)

**Implemented enhancements:**

- Manage data safely within the client [\#9](https://github.com/parallaxsecond/parsec-client-rust/issues/9)
- Upgrade dependencies versions [\#48](https://github.com/parallaxsecond/parsec-client-rust/pull/48) ([hug-dev](https://github.com/hug-dev))

## [0.8.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.8.0) (2020-08-18)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.7.1...0.8.0)

**Implemented enhancements:**

- Added has compute and compare [\#45](https://github.com/parallaxsecond/parsec-client-rust/pull/45) ([sbailey-arm](https://github.com/sbailey-arm))

**Merged pull requests:**

- Add test for psa\_generate\_random [\#47](https://github.com/parallaxsecond/parsec-client-rust/pull/47) ([joechrisellis](https://github.com/joechrisellis))
- Added raw key agreement and test [\#46](https://github.com/parallaxsecond/parsec-client-rust/pull/46) ([sbailey-arm](https://github.com/sbailey-arm))
- Added aead encrypt and decrypt [\#44](https://github.com/parallaxsecond/parsec-client-rust/pull/44) ([sbailey-arm](https://github.com/sbailey-arm))
- Add support for ListAuthenticators operation [\#43](https://github.com/parallaxsecond/parsec-client-rust/pull/43) ([joechrisellis](https://github.com/joechrisellis))
- Add Rust client support for `psa\_generate\_random` operation [\#42](https://github.com/parallaxsecond/parsec-client-rust/pull/42) ([joechrisellis](https://github.com/joechrisellis))

## [0.7.1](https://github.com/parallaxsecond/parsec-client-rust/tree/0.7.1) (2020-07-22)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.7.0...0.7.1)

**Implemented enhancements:**

- Publish a new version [\#40](https://github.com/parallaxsecond/parsec-client-rust/pull/40) ([hug-dev](https://github.com/hug-dev))
- Implement `Error` and `Display` traits for `parsec\_client::error::Error` [\#39](https://github.com/parallaxsecond/parsec-client-rust/pull/39) ([joechrisellis](https://github.com/joechrisellis))

**Merged pull requests:**

- Added asymmetric encrypt and decrypt [\#36](https://github.com/parallaxsecond/parsec-client-rust/pull/36) ([sbailey-arm](https://github.com/sbailey-arm))

## [0.7.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.7.0) (2020-07-15)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.6.0...0.7.0)

**Implemented enhancements:**

- Added PsaExportKey [\#38](https://github.com/parallaxsecond/parsec-client-rust/pull/38) ([sbailey-arm](https://github.com/sbailey-arm))

## [0.6.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.6.0) (2020-07-07)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.5.0...0.6.0)

## [0.5.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.5.0) (2020-07-02)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.4.0...0.5.0)

**Implemented enhancements:**

- Add memory wiping functionality [\#32](https://github.com/parallaxsecond/parsec-client-rust/pull/32) ([ionut-arm](https://github.com/ionut-arm))

**Fixed bugs:**

- Fix the fs check on the socket folder feature [\#35](https://github.com/parallaxsecond/parsec-client-rust/pull/35) ([hug-dev](https://github.com/hug-dev))
- Import the newer interface [\#34](https://github.com/parallaxsecond/parsec-client-rust/pull/34) ([hug-dev](https://github.com/hug-dev))

**Merged pull requests:**

- Change socket location and add checks [\#33](https://github.com/parallaxsecond/parsec-client-rust/pull/33) ([hug-dev](https://github.com/hug-dev))

## [0.4.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.4.0) (2020-06-05)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.3.0...0.4.0)

**Implemented enhancements:**

- Import the newest interface and increase version [\#30](https://github.com/parallaxsecond/parsec-client-rust/pull/30) ([hug-dev](https://github.com/hug-dev))
- Import the new interface [\#29](https://github.com/parallaxsecond/parsec-client-rust/pull/29) ([hug-dev](https://github.com/hug-dev))

## [0.3.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.3.0) (2020-05-06)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.2.0...0.3.0)

**Implemented enhancements:**

- Expose the interface through the client, even for testing [\#25](https://github.com/parallaxsecond/parsec-client-rust/issues/25)
- Add Send and Sync to trait objects [\#27](https://github.com/parallaxsecond/parsec-client-rust/pull/27) ([hug-dev](https://github.com/hug-dev))

## [0.2.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.2.0) (2020-04-24)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/0.1.0...0.2.0)

**Implemented enhancements:**

- Resurface full interface as part of core [\#26](https://github.com/parallaxsecond/parsec-client-rust/pull/26) ([ionut-arm](https://github.com/ionut-arm))

## [0.1.0](https://github.com/parallaxsecond/parsec-client-rust/tree/0.1.0) (2020-04-22)

[Full Changelog](https://github.com/parallaxsecond/parsec-client-rust/compare/a574ae6083652a7dd57e5e99fbadd05a423143fc...0.1.0)

**Implemented enhancements:**

- Make the CoreClient really dumb [\#19](https://github.com/parallaxsecond/parsec-client-rust/issues/19)
- Extract UnixSocket-specific functionality out of RequestHandler [\#13](https://github.com/parallaxsecond/parsec-client-rust/issues/13)
- Create test framework [\#7](https://github.com/parallaxsecond/parsec-client-rust/issues/7)
- Implement client-specific error structures [\#5](https://github.com/parallaxsecond/parsec-client-rust/issues/5)
- Implement configuration [\#3](https://github.com/parallaxsecond/parsec-client-rust/issues/3)
- Add methods for modifying timeout of IPC handlers [\#24](https://github.com/parallaxsecond/parsec-client-rust/pull/24) ([ionut-arm](https://github.com/ionut-arm))
- Make `implicit\_provider` optional [\#23](https://github.com/parallaxsecond/parsec-client-rust/pull/23) ([ionut-arm](https://github.com/ionut-arm))
- Add getters for auth\_data and implicit\_provider [\#22](https://github.com/parallaxsecond/parsec-client-rust/pull/22) ([ionut-arm](https://github.com/ionut-arm))
- Add contributing guidelines link [\#21](https://github.com/parallaxsecond/parsec-client-rust/pull/21) ([hug-dev](https://github.com/hug-dev))
- Refactor low level clients [\#20](https://github.com/parallaxsecond/parsec-client-rust/pull/20) ([ionut-arm](https://github.com/ionut-arm))
- Add failing IPC test [\#15](https://github.com/parallaxsecond/parsec-client-rust/pull/15) ([ionut-arm](https://github.com/ionut-arm))
- Factor IPC handling out of the request handler [\#14](https://github.com/parallaxsecond/parsec-client-rust/pull/14) ([ionut-arm](https://github.com/ionut-arm))
- Add testing framework and unit tests [\#12](https://github.com/parallaxsecond/parsec-client-rust/pull/12) ([ionut-arm](https://github.com/ionut-arm))
- Make inner attributes configurable [\#10](https://github.com/parallaxsecond/parsec-client-rust/pull/10) ([ionut-arm](https://github.com/ionut-arm))
- Add client-specific error types [\#8](https://github.com/parallaxsecond/parsec-client-rust/pull/8) ([ionut-arm](https://github.com/ionut-arm))
- Seed initial client [\#1](https://github.com/parallaxsecond/parsec-client-rust/pull/1) ([ionut-arm](https://github.com/ionut-arm))

**Closed issues:**

- Rename methods to contain `psa\_` prefix [\#17](https://github.com/parallaxsecond/parsec-client-rust/issues/17)
- Improve documentation [\#2](https://github.com/parallaxsecond/parsec-client-rust/issues/2)

**Merged pull requests:**

- Add "psa\_" prefix to method names. [\#18](https://github.com/parallaxsecond/parsec-client-rust/pull/18) ([ionut-arm](https://github.com/ionut-arm))
- Add documentation [\#16](https://github.com/parallaxsecond/parsec-client-rust/pull/16) ([ionut-arm](https://github.com/ionut-arm))
- Update the way copyrights are displayed [\#11](https://github.com/parallaxsecond/parsec-client-rust/pull/11) ([ionut-arm](https://github.com/ionut-arm))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
