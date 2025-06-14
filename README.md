```rust
fn main() {

    let me = WhoAmI::builder()
        .name("Zaid")
        .age(18)
        .origin("Sri Lanka")
        .interests(vec!["🧠 Coding", "🎮 Video Games"])
        .build();

    me.launch();
}
```
