# Require

```swift

let value: String?

// Catch error if value is nil
let v: String = try value.require()

// Cause fatalError if value is nil
let v: String = value.unsafeRequire()

```

