# 再現手順

```
$ pod install
$ carthage bootstrap --platform iOS --use-ssh --no-use-binaries --new-resolver
$ xcodebuild
```

# 環境

- coocapods 1.6.0.beta.1
- xcode10
