### 9/4 
Hours: 10
  - Fix returndatatests that were accidentally deleted when cleaning commit history.  https://github.com/ethereum/tests/pull/290. 
  - Add more tests to 'goodOpcodes', improve test cases. https://github.com/ethereum/tests/pull/289
### 9/5
Hours: 8 
  - Investigated issue with EthereumJS failing blockchain tests under EIP158.  identified '34b2756789401b3f8338f1afb10f02d2de236a72' as the revision where error was introduced.
### 9/6 
Hours: 8
  - Investigated EthereumJS failing BLOCKHASH tests.  
  - Cleanup and updates for Ethereumjs-testing.
### 9/8 
Hours: 6
  - Investigated EthereumJS failing BLOCKHASH tests.  
  - EthereumJS weekly meeting.  
  - All-core devs meeting.
### 9/9 
Hours: 3
  - Investigated EthereumJS failing BLOCKHASH tests.  Discovered that ethereumjs-blockchain is failing on master branch.  Identified commit where the error appears.
### 9/10 
Hours: 6
  - Fix for race condition in ethereumjs-blockchain: ...   
  - Implementation of EIP 698 
### 9/11 
Hours: 8
  - Debugging error with Byzantium receipt root (ethereumjs).  
  - Investigate implementation of transaction receipt tracing in testeth.
### 9/12 
Hours: 9
  - Work on EthereumJS docker image, trace equivalence testing.  
  - Fix trie-receipts for Byzantium implementation
### 9/13
Hours: 8
  - Docker image and Trace equivalence testing for EthereumJS: https://github.com/holiman/evmlab/pull/10

### 9/14
Hours: 8
  - Add support for testing with a custom state test in EthereumJS: https://github.com/ethereumjs/ethereumjs-testing/pull/13, https://github.com/ethereumjs/ethereumjs-vm/pull/202

### 9/15
Hours: 8
  - Complete tests for all good opcodes in contract init (testing): 

### 9/16
Hours: 4
  - https://github.com/holiman/evmlab/pull/11

### 9/17
Hours: 4
  - Debugging failing precompile tests

### 9/18
Hours: 8
  - Debugging failing precompile tests

### 9/19
Hours: 7
  - Fix for testeth cpp-ethereum Docker image issue (testing): https://github.com/holiman/evmlab/pull/13
  - Disable GeneralStateTests suite blockchain tests (EthereumJS-VM): https://github.com/ethereumjs/ethereumjs-vm/pull/206

### 9/20
Hours: 8
  - Utility script to produce concise comparisons of testing output between different versions of EthereumJS-VM: https://github.com/ethereumjs/ethereumjs-vm/pull/207
  - Fix calculation of uncle/nephew reward for Byzantium implementation of EthereumJS-VM: https://github.com/jwasinger/ethereumjs-vm/commit/74ede8a8df33a11f564d355f40edc3eb928afa66

### 9/21
Hours: 6
  - Creation of a meta issue to describe progress of Byzantium implementation of EthereumJS-VM: https://github.com/ethereumjs/ethereumjs-vm/issues/209
  - Discussion and formulation of a release process for Byzantium implementation of EthereumJS-VM

### 9/22
Hours: 6
  - All Core Devs meeting
  - EthereumJS meeting
  - https://github.com/ethereum/cpp-ethereum/pull/4542
