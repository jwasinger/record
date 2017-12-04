## 12/1 
Hours: 0 

## 12/2
### EWASM:
Hours: 5
 - WIP: Ethereum state tests transcompiled to EWASM at runtime and run through ethereumjs-vm: https://github.com/jwasinger/ethereumjs-vm#wip/ewasm

## 12/3
### EWASM:
Hours: 8
 - Attempted to transcompile ethereum tests to ewasm at runtime in ethereumjs-vm.  Spent time debugging a memory leak when invoking `evm2wasm` in nested asynchronous code.  Separate approach is to transcompile all the state tests to EWASM as part of a build process. See: https://github.com/jwasinger/ewasm-tests
