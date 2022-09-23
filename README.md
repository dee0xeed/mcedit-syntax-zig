# Zig language syntax highlighting for mcedit
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
