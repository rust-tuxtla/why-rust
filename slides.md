![](img/rust-logo.png)
<!-- .element: style="margin-top: -5%;" -->
## Introduction

#### [Mario Garcia](http://mattdark.github.io) · [@mariogmd](https://twitter.com/mariogmd)

---

## What is Rust?

***

### A systems programming language focus on:

<br>

<span class="fragment">safety</span><span class="fragment">, speed</span><span class="fragment">, and concurrency.</span>

<!-- .element: class="fragment" -->

---

## Installing Rust

### Linux or Mac:

```

curl -sSf https://static.rust-lang.org/rustup.sh | sh

```

---

## Hello world!

```
//main.rs
fn main()
 {
  println!("Hello world!");
 }
```

---

## Running

```
  $ rustc main.rs
  $ ./main
  Hello world!
```

---

## Rust Sintax

---

## variables

```
  let name = expression;
```

---

## Primitive Types

---

## Booleans

```
  let x = true;
  let y: bool = true;
```

---

## char

```
  let x = 'x';
```

---

## Numeric Types

```
  let x = 42; // x has type i32
  let y = 1.0; // y has type f64
```

---

## Arrays

```
  let a = [1, 2, 3]; // a: [i32; 3]
  let mut m = [1, 2, 3]; // m: [i32; 3]
```

---

## functions

```
fn name(arg: Type) -> ReturnType
 {
  statements;
 }
```

---

## function call

```
  fn_name(args);
```

---

## println

```
  println!("string {} literal", expressions);
```

---

![](img/cargo-logo.png)

## Cargo

---

## What is Cargo?

***

### Cargo is Rust’s build system and package manager.

---

## New project with Cargo

```
  $ cargo new hello_world --bin
```

---

## Manifest

```
[package]
name = "hello_world" # the name of the package
version = "0.1.0"    # the current version, obeying semver
authors = ["you@example.com"]
```

---

## Build & Run

```
  $ cargo build
  $ cargo run
```

---

## Servo

---

## What is Servo?

***

#### Servo is a modern, performant browser engine designed to be appropriate for applications including embedded use.

---

## Learn More

_[rust-lang.org](https//rust-lang.org)_

___

[@mariogmd](https://twitter.com/mariogmd)

mattdark@mozilla-mexico.org