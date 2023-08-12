# Zig language syntax highlighting for mcedit
![zig-syntax-for-mcedit](https://repository-images.githubusercontent.com/535814296/08dc2784-5269-4fe2-b2dc-65d4523a6cbe)
## How to use
  - put `zig.syntax` file into `/usr/share/mc/syntax` directory
  - add following lines to `/usr/share/mc/syntax/Syntax`
  ```
  file .\*\\.(zig)$ zig\sProgram
  include zig.syntax
  ```
  right before these lines (which are in the very end)
  ```
  file .\* unknown
  include unknown.syntax
  ```
