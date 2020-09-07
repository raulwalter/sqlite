# GORM Sqlite Encrypt Driver

## USAGE

```go
import (
  "github.com/raulwalter/sqlite"
  "gorm.io/gorm"
)

// github.com/CovenantSQL/go-sqlite3-encrypt
db, err := gorm.Open(sqlite.Open("file:gorm.db?_crypto_key=SECRET&cache=shared"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.