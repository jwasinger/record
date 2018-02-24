### 2/1:
#### Testing:
Hours: 8
 - test for returndatacopy with large offset

### 2/2:
#### Testing
Hours: 8

### 2/3:
#### Stateless Client Prototyping
Hours: 8
 - Researching stateless client material.  Reading {asynchronous accumulators paper}

### 2/4:
#### EWASM
Hours:
 - 4

### 2/5
#### EWASM
Hours: 

### 2/8
Hours: 9.5

#### EthereumJS
 - Trying to solve test failures in new modexp test cases

#### Other/Go-ethereum
 - Added SHR opcode to go-ethereum: https://github.com/jwasinger/go-ethereum/tree/constantinople

### 2/14
#### EWASM
Hours: 7
 - working on running state tests suite through hera
 - EWASM weekly meeting

### 2/15
#### EWASM
Hours: 4
 - working on running state tests suite through hera

### 2/16
#### EWASM
Hours: 10
 - working on running state tests suite through hera 
 - debugging binary corruption issue with NodeJS buffer

### 2/17
#### EWASM
Hours: 10
 - working on running state tests suite through hera 
 - Working on Hera in docker container
 - Debugging why cpp-eth/Hera wasn't mining any blocks (had to rebuild from scratch which fixed the issue....)

### 2/19
#### EWASM
Hours: 2
 - Working on cpp-eth/hera/jsonrpcproxy running in docker.  Trying to solve IPC issue where pythonrpcproxy on host cannot communicate with socket mounted from container

### 2/21
Hours: 2.5
 - Working on cpp-eth/hera/jsonrpcproxy running in docker.  Trying to solve IPC issue where pythonrpcproxy on host cannot communicate with socket mounted from container

### 2/23
Hours: 2.5
 - All Core Devs meeting
 - researching Blake2B hash function

### 2/24
Hours: 4
 - Brainstorming ways to compare speed of cpp-ethereum's keccak implementation to a WASM implementation that @axic wrote, realized that the WASM opcodes themselves should be benchmarked.
 - Started an implementation of debug benchmarking calls in Hera only to realize that it is not useful
