```rust
fn main() {
    let who_am_i = WhoAmI::builder()
        .name("Zaid".to_owned())
        .age(18)
        .country("Sri Lanka".to_owned())
        .build();
}

struct WhoAmI {
    name: String,
    age: u8,
    country: String,
}

impl WhoAmI {

    pub fn builder() -> WhoAmIBuilder {
        WhoAmIBuilder::default()
    }
}

#[derive(Default)]
struct WhoAmIBuilder {


    name: String,
    age: u8,
    country: String,
}

impl WhoAmIBuilder {



    pub fn name(mut self, name: String) -> Self {
        self.name = name;
        self
    }

    pub fn age(mut self, age: u8) -> Self {
        self.age = age;
        self
    }

    pub fn country(mut self, country: String) -> Self {
        self.country = country;
        self
    }

    pub fn build(self) -> WhoAmI {
        WhoAmI {
            name: self.name,
            age: self.age,
            country: self.country,
        }
    }
}
```
