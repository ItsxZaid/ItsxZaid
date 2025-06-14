```rust
fn main() {

    let me = WhoAmI::builder()
        .name("Zaid")
        .age(18)
        .origin("Sri Lanka")
        .build();

    me.launch();
}

```
