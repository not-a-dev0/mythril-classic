# Analysis results for test-filename.sol

## External call
- SWC ID: 107
- Type: Informational
- Contract: Unknown
- Function name: `thisisfine()`
- PC address: 661
- Estimated Gas Usage: 643 - 1254

### Description

The contract executes a function call to an external address. Verify that the code at this address is trusted and immutable.

## Unchecked CALL return value
- SWC ID: 104
- Type: Informational
- Contract: Unknown
- Function name: `thisisfine()`
- PC address: 661
- Estimated Gas Usage: 1361 - 35972

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.

## External call
- SWC ID: 107
- Type: Informational
- Contract: Unknown
- Function name: `callstoredaddress()`
- PC address: 779
- Estimated Gas Usage: 687 - 1298

### Description

The contract executes a function call to an external address. Verify that the code at this address is trusted and immutable.

## Unchecked CALL return value
- SWC ID: 104
- Type: Informational
- Contract: Unknown
- Function name: `callstoredaddress()`
- PC address: 779
- Estimated Gas Usage: 1405 - 36016

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.

## External call
- SWC ID: 107
- Type: Informational
- Contract: Unknown
- Function name: `reentrancy()`
- PC address: 858
- Estimated Gas Usage: 709 - 1320

### Description

The contract executes a function call to an external address. Verify that the code at this address is trusted and immutable.

## Unchecked CALL return value
- SWC ID: 104
- Type: Informational
- Contract: Unknown
- Function name: `reentrancy()`
- PC address: 858
- Estimated Gas Usage: 6441 - 61052

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.

## External call to user-supplied address
- SWC ID: 107
- Type: Warning
- Contract: Unknown
- Function name: `calluseraddress(address)`
- PC address: 912
- Estimated Gas Usage: 335 - 616

### Description

The contract executes a function call with high gas to a user-supplied address. Note that the callee can contain arbitrary code and may re-enter any function in this contract. Review the business logic carefully to prevent unanticipated effects on the contract state.

## Unchecked CALL return value
- SWC ID: 104
- Type: Informational
- Contract: Unknown
- Function name: `calluseraddress(address)`
- PC address: 912
- Estimated Gas Usage: 1055 - 35336

### Description

The return value of an external call is not checked. Note that execution continue even if the called contract throws.
