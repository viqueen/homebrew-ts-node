## homebrew-ts-node

### install it

```bash
brew tap viqueen/ts-node
brew install ts-node
```

### update on new releases

* get latest package url, and sha
```bash
npm view ts-node dist.tarball
curl -O <package-url>
```

* get and compare sha checksum
```bash
npm view ts-node dist.shasum
shasum <package>
```

* get sha256 checksum
```bash
shasum -a 256 <package>
```
