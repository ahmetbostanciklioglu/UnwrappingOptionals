# UnwrappingOptionals
Unwrap optionals with if let




**Unwrapping:**

```
var unwrappingOptinalProperty: String? = nil

if let unwrappingOptinalProperty {
    print("\(unwrappingOptinalProperty.count)")
} else {
    print("An emtpy optional string (String?)")
}


func optionalStringReturningFunction() -> String? {
    "Ahmet"
}

if let nameString = optionalStringReturningFunction() {
    print("\(nameString)")
}else {
    print("An emtpy optional string (String?) returning function")
}
```
