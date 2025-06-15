```rust
fn main() {
    let me = WhoAmI::builder()
        .name("Zaid")
        .age(18)
        .origin("Sri Lanka")
        .technologies: vec!["Rust", "TypeScript", "React", "Node.js", "Go", "Python"],
        .interests(vec!["🧠 Coding", "🎮 Video Games"])
        .build();

    me.launch();
}
```
