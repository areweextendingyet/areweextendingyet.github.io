# [areweextendingyet.github.io](https://areweextendingyet.github.io) - [Contribute](https://github.com/areweextendingyet/areweextendingyet.github.io/)

# Yes, it is possible!
### And already happening.

## Learning Rust <=> FFI

- 📹 [RustFest Rome 2018 - Yiming Jing : One Thousand Ways to Die in Rust FFI](https://www.youtube.com/watch?v=kGj-Fxg5txQ)
- 📹 [RustConf 2018 - Embedding Rust in C/C++ by Katharina](https://www.youtube.com/watch?v=x9acx2zgx4Q)
- 📹 [Hello Rust! #8 - Let's write a Python module! (Tutorial, FFI, pyo3)](https://www.youtube.com/watch?v=D9r__qxtRMQ)
- 📹 [RustCamp - Using Rust from C... or Any Language by Yehuda Katz](https://www.youtube.com/watch?v=GktVBv76fe0)
- 📚 [Rust Book: FFI](https://doc.rust-lang.org/book/ffi.html)
- 📚 [Rust Nomicon: Official FFI Guide](https://doc.rust-lang.org/nomicon/ffi.html)
- 📚 [The (unofficial) Rust FFI Guide](https://michael-f-bryan.github.io/rust-ffi-guide/overview.html)
- 📚 [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/)
- [FFI examples written in Rust](https://github.com/alexcrichton/rust-ffi-examples)
- 🔧 [Bindgen](https://rust-lang.github.io/rust-bindgen/) - Automatically generates Rust FFI bindings to C (and some C++) libraries. 
- 🔧 [Crossgen](https://github.com/yoshuawuyts/crossgen) - Cross compilation template generator 

## Languages

### C
  * [rlhunt/cbindgen](https://github.com/eqrion/cbindgen) — generates C header files from Rust source files. Used in Gecko for WebRender [<img src="https://api.travis-ci.org/eqrion/cbindgen.svg?branch=master">](https://travis-ci.org/eqrion/cbindgen)
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) — generates C header files from Rust source files [<img src="https://api.travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master">](https://travis-ci.org/Sean1708/rusty-cheddar)

### C++
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) — a Rust bindings generator

### Dart
 Not yet, as [FFI](https://github.com/dart-lang/sdk/issues/34452) is still stabilizing. But it is possible to use Native extensions (Flutter) or WebAssembly/JS for Web.

### Erlang
  * [hansihe/Rustler](https://github.com/hansihe/Rustler) — safe Rust bridge for creating Erlang NIF functions [<img src="https://api.travis-ci.org/hansihe/rustler.svg?branch=master">](https://travis-ci.org/hansihe/rustler)

### Go
  * [rustgo: calling Rust from Go with near-zero overhead](https://blog.filippo.io/rustgo/) - Blog post
  * [rure](https://github.com/BurntSushi/rure-go) - Go library using Rust Regex crate
  * [rust + golang](https://github.com/medimatrix/rust-plus-golang)

### Haskell
  * [mgattozzi/curryrs](https://github.com/mgattozzi/curryrs) — Bridge the gap between Haskell and Rust
  * [mgattozzi/haskellrs](https://github.com/mgattozzi/haskellrs) — Rust in Haskell FFI Example
  * [mgattozzi/rushs](https://github.com/mgattozzi/rushs) — Haskell in Rust FFI Example

### Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni) — use Java from Rust [<img src="https://api.travis-ci.org/bennettanderson/rjni.svg?branch=master">](https://travis-ci.org/GravityScore/RustJNI)
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) — use Rust from Java [<img src="https://api.travis-ci.org/drrb/java-rust-example.svg?branch=master">](https://travis-ci.org/drrb/java-rust-example)
  * [kud1ing/rucaja](https://github.com/kud1ing/rucaja) [[rucaja](https://crates.io/crates/rucaja)] — use Java from Rust [<img src="https://api.travis-ci.org/kud1ing/rucaja.svg?branch=master">](https://travis-ci.org/kud1ing/rucaja)
  * [prevoty/jni-rs](https://github.com/jni-rs/jni-rs) [[jni](https://crates.io/crates/jni)] — use Rust from Java [<img src="https://api.travis-ci.org/prevoty/jni-rs.svg?branch=master">](https://travis-ci.org/prevoty/jni-rs)
  * [rawrasaur/rust-jdbc](https://github.com/rawrasaur/rust-jdbc) — uses JDBC from Rust [<img src="https://api.travis-ci.org/rawrasaur/rust-jdbc.svg?branch=master">](https://travis-ci.org/rawrasaur/rust-jdbc)
  * [sfackler/rust-jni-sys](https://github.com/sfackler/rust-jni-sys) [[jni-sys](https://crates.io/crates/jni-sys)] — Rust definitions corresponding to jni.h [<img src="https://api.travis-ci.org/sfackler/rust-jni-sys.svg?branch=master">](https://travis-ci.org/sfackler/rust-jni-sys)
  * [rust-jna-example (Java/Android/Gradle)](https://github.com/bltavares/rust-over-jna-example)

### Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) — Lua 5.3 bindings for Rust [<img src="https://api.travis-ci.org/jcmoyer/rust-lua53.svg?branch=master">](https://travis-ci.org/jcmoyer/rust-lua53)
  * [kballard/rust-lua](https://github.com/kballard/rust-lua) — Safe Rust bindings to Lua 5.1 [<img src="https://api.travis-ci.org/kballard/rust-lua.svg">](https://travis-ci.org/kballard/rust-lua)
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) — Zero-cost high-level lua 5.3 wrapper for Rust [<img src="https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master">](https://travis-ci.org/tickbh/td_rlua)
  * [tomaka/hlua](https://github.com/tomaka/hlua) — Rust library to interface with Lua [<img src="https://api.travis-ci.org/tomaka/hlua.svg?branch=master">](https://travis-ci.org/tomaka/hlua)

### Node.js
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) — use Rust from Node.js [<img src="https://api.travis-ci.org/neon-bindings/neon.svg?branch=master">](https://travis-ci.org/neon-bindings/neon)

### Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) — Objective-C Runtime bindings and wrapper for Rust

### Perl
  * [vickenty/mi-rust](https://github.com/vickenty/mi-rust) — Adds support to M::I for building modules with Cargo
  * [vickenty/perl-xs](https://github.com/vickenty/perl-xs) — Create Perl XS modules using Rust [<img src="https://api.travis-ci.org/vickenty/perl-xs.svg?branch=master">](https://travis-ci.org/vickenty/perl-xs)

### Python
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) — extension for python setuptools that allows you to distribute dynamic linked libraries in Python wheels in the most portable way imaginable.
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) — Python bindings [<img src="https://api.travis-ci.org/dgrunwald/rust-cpython.svg?branch=master">](https://travis-ci.org/dgrunwald/rust-cpython)
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) — Rust bindings for the Python interpreter [<img src="https://api.travis-ci.org/PyO3/pyo3.svg?branch=master">](https://travis-ci.org/PyO3/pyo3)

### R
  * [rustr/rustr](https://github.com/rustr/rustr) — use Rust from R, and use R in Rust [<img src="https://api.travis-ci.org/rustr/rustr.svg?branch=master">](https://travis-ci.org/rustr/rustr)

### Ruby
  * [d-unseductable/ruru](https://github.com/d-unseductable/ruru) — native Ruby extensions written in Rust and vice versa [<img src="https://api.travis-ci.org/d-unseductable/ruru.svg?branch=master">](https://travis-ci.org/d-unseductable/ruru)
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) — official fork of d-unseductable/ruru [![Build Status](https://travis-ci.org/danielpclark/rutie.svg?branch=master)](https://travis-ci.org/danielpclark/rutie)
  * [tildeio/helix](https://github.com/tildeio/helix) — native Ruby extensions written in Rust [<img src="https://api.travis-ci.org/tildeio/helix.svg?branch=master">](https://travis-ci.org/tildeio/helix)
#### mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) — mruby safe bindings for Rust [<img src="https://api.travis-ci.org/anima-engine/mrusty.svg?branch=master">](https://travis-ci.org/anima-engine/mrusty)

### Web Assembly
  * [rustwasm/wasm-pack](https://github.com/rustwasm/wasm-pack) — :package: :sparkles: pack up the wasm and publish it to npm! [<img src="https://api.travis-ci.org/rustwasm/wasm-pack.svg?branch=master">](https://travis-ci.org/rustwasm/wasm-packn)
  * [rustwasm/wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) — A project for facilitating high-level interactions between wasm modules and JS. [<img src="https://api.travis-ci.org/rustwasm/wasm-bindgen.svg?branch=master">](https://travis-ci.org/rustwasm/wasm-bindgen)


# See also

  - [Are we IDE yet?](https://areweideyet.com/)
  - [Are we (Machine) Learning yet?](https://www.arewelearningyet.com/)
  - [Are we Web yet?](http://www.arewewebyet.org/)
  - [Are we game yet?](http://arewegameyet.com/)
  - [awesome-rust](https://github.com/rust-unofficial/awesome-rust) - A curated list of links for Awesome Rust Content
  - [rust-learning](https://github.com/ctjhoa/rust-learning) - A curated list of content to learn Rust
