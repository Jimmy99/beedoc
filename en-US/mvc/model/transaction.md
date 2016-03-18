---
name: Transaction
sort: 7
---

# Transaction

ORM supports basic transaction implementation

```go
o := NewOrm()
err := o.Begin()
// transaction process
...
...
// All the queries which use o Ormer in this process are included the transaction
if SomeError {
	err = o.Rollback()
} else {
	err = o.Commit()
}
```
