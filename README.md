# Require

```swift

let value: String?

// Catch error if value is nil
try value.require()

// Cause fatalError if value is nil
value.unsafeRequire()

```

