<!--suppress ALL -->

# 👋 ஐ Cy6ber7um ஐ <a href="https://github.com/Cy6ber7um"><img alt="GitHub Followers" src="https://img.shields.io/github/followers/Cy6ber7um?style=flat&logo=github" /></a> <a href="https://twitter.com/Cy6ber7um"><img alt="Twitter Followers" src="https://img.shields.io/twitter/follow/Cy6ber7um?style=flat&logo=twitter" /></a>

<img align="right" width="400" src="./Images/Raining.gif" />

```Rust
#![no_std] // This is a minimal kernel.
#![no_main]

use core::panic::PanicInfo;

#[panic_handler]
fn panic(_info: &PanicInfo) -> ! { loop {} }

#[no_mangle]
pub extern "C" fn _start() -> ! {
    let message = "Hi, I am Enabled Fish!"; // ☬
    let buffer = 0xb8000 as *mut u8;
    for (i, &b) in message.as_bytes().iter().enumerate() {
        unsafe { // ☈
            *buffer.offset(i as isize * 2) = b;
            *buffer.offset(i as isize * 2 + 1) = 0xb;
        }
    }
    loop {}
}
```

# 📕 ❀ Environment ❀

<code><img height="30" width="30" src="./Images/Rust.png"></code>
<code><img height="30" width="30" src="./Images/Cpp.png"></code>
<code><img height="30" width="30" src="./Images/Csharp.png"></code>
<code><img height="30" width="30" src="./Images/Nodejs.png"></code>
<code><img height="30" width="30" src="./Images/Reactjs.png"></code>
<code><img height="30" width="30" src="./Images/Golang.png"></code>
<code><img height="30" width="30" src="./Images/Python.png"></code>
<code><img height="30" width="30" src="./Images/Llvm.png"></code>
<code><img height="30" width="30" src="./Images/Jvm.png"></code>
<code><img height="30" width="30" src="./Images/Dotnet.png"></code>

# 📃 〄 Analysis 〄

<img width="40%" align="left" src="https://github-readme-stats.vercel.app/api?username=Cy6ber7um&include_all_commits=true&role=OWNER,ORGANIZATION_MEMBER&count_private=true&show_icons=true&theme=radical" />
<img width="56%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Cy6ber7um&theme=radical" />

# 📞 ❅ Contact ❅

```text
Github: @Cy6ber7um
Twitter: @Cy6ber7um
Mail: Cy6ber7um@gmail.com
```

[![☬](https://komarev.com/ghpvc/?username=Cy6ber7um&stype=flat)](https://github.com/Cy6ber7um)
[![☬](https://img.shields.io/badge/@Cy6ber7um-%23181717?style=flat&logo=github)](https://github.com/Cy6ber7um)
