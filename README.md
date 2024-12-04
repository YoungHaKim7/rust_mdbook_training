# rust_mdbook_training

- easy rust 보면서 흉내내기
  - https://github.com/Dhghomon/easy_rust

- https://rust-lang.github.io/mdBook/

# install

```bash
cargo install mdbook

```

- mdbook init

- 대략적인 파일 구조
  
```bash

$ eza -la --icons -TL2
drwxr-xr-x    - gy-gyoung  2 Dec 18:42  .
.rw-r--r--    5 gy-gyoung  2 Dec 18:41 ├──  .gitignore
drwxr-xr-x    - gy-gyoung  2 Dec 18:41 ├──  book
.rw-r--r--   95 gy-gyoung  2 Dec 18:41 ├──  book.toml
drwxr-xr-x    - gy-gyoung  2 Dec 18:42 ├──  rust_kr
drwxr-xr-x    - gy-gyoung  2 Dec 18:42 │  ├──  .git
.rw-r--r--  794 gy-gyoung  2 Dec 18:42 │  ├──  .gitignore
.rw-r--r-- 1.1k gy-gyoung  2 Dec 18:42 │  ├──  LICENSE
.rw-r--r--  224 gy-gyoung  2 Dec 18:42 │  └──  README.md
drwxr-xr-x    - gy-gyoung  2 Dec 18:41 └──  src
.rw-r--r--   12 gy-gyoung  2 Dec 18:41    ├──  chapter_1.md
.rw-r--r--   41 gy-gyoung  2 Dec 18:41    └──  SUMMARY.md

```

- 실시간으로 보면서 편집하기
 
```
$ mdbook serve --open 
```

- Firefox

```
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

- Chrome:
```
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```

- https://github.com/rinthel/rust-lang-book-ko
