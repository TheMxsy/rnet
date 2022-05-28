# rnet
Progressive net application development to discover best practices in Rust-lang
ecosystem. 

On mac systems:
shell: 
>rustup target add x86_64-unknown-linux-musl
>brew install FiloSottile/musl-cross/musl-cross  
>cargo build --target=x86_64-unknown-linux-musl 

in file .cargo/config add following:
[target.x86_64-unknown-linux-musl]
linker = "x86_64-linux-musl-gcc"