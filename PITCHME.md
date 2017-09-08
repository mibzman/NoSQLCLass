![LOGO](https://hungerperks.com/images/HungerPerks-Log-with-Tagline-No-R.png)

<br>
<span style="color:gray">Databases & More</span>

---

## Our Stack:
<br>
### Frontend:
- Angular2 Web
- Ionic2 Mobile App

### Backend:
- Golang
- PostgreSQL
- Gorm Object-Relational Mapper

---

### Golang:


- Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.


- a compiled, statically typed language in the tradition of Algol and C, with garbage collection, limited structural typing, memory safety features and CSP-style concurrent programming features added.

---

### PostgreSQL


- an object-relational database management system (ORDBMS) with an emphasis on extensibility and standards compliance.


#### PostGIS


- PostGIS is a spatial database extender for PostgreSQL object-relational database. It adds support for geographic objects allowing location queries to be run in SQL


---

### Gorm


- Object-relational mapping a programming technique for converting data between incompatible type systems using object-oriented programming languages. This creates, in effect, a "virtual object database" that can be used from within the programming language

---

### Our experience with Object-Relational Mappers

- useful for simple operations
	- entire object is read into memory, including it's children

- for more complex operations you can still run standard queries

---

## Golang?
<sup>LOL no generics</sup>

### Advantages:
- As many interesting libraries as python, but with most of the language features from C++
- Fast compile times
- multiple return values

### Disadvantages:
- Bad Dependency Management
- No generics
- meme-ey community
- Typical error management is extremely verbose

```go
Result, err := DoThing()
if err := nil {
	return err
}
```
