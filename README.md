# EE480Assignment4

## Approach
  1. Separate existing pipelined implementation into a single control unit and single PE. Pass through all operations and
  add any wires as necessary.
  2. Remove jump, call, ret from PE and pass noOps from CU.
  3. Add ability to read the enable stack of every PE in the CU.
  4. Implement jumpf in the CU
  5. Implement gor, left, and right
