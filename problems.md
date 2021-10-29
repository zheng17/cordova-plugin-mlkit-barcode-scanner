# Problems

## Todo

- tag version `2.1.3`, which hasn't been tagged yet
  - should have been `3.0.0` due to multiple breaking changes
    - types can't be accessed anymore through namespace `CordovaPluginMLKitBarcodeScanner`
    - `cancelled` was removed from `Result`
    - `scan()` doesn't allow `{}` as `userOptions` anymore
    - `failureCallback` now doesn't return an instance of `Error`
- multiple change requests were added in code and `README.md` marked by `// FIXME`
- add beep sound upon scan (if not already implemented)
- release new version `3.0.0`

## Already fixed

- fixed typo in `README.md` (commit debb8c303e67c46119e9e6d80931d68ace2e523b)
- formatted `README.md` with prettier (commit e6b16a0555536bb01e3b616e6da027fc47a2c265)
- types are now exposed properly (commit acb55994ea0e83676a59f3e528abc0247f709f13)
- improved usage of types (commit 898a7716d51afa032cd2854a3e986920315b0ee5)
- improved wording in `README.md` (commit bc9d016eab2abbbae3cb8336ffd31a5dcf0af58c)
