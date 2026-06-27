# 4-bit-controllable-counter
Combines synchronous reset, enable, and direction control into a single counter module.
Key Concepts Reinforced

<= (non-blocking assignment) for sequential logic inside clocked blocks
Implicit hold behavior when no assignment occurs in a clocked always block
Signal width and literal syntax (4'b0000, 1'b1, etc.)
Testbench structure: reg for driven signals, wire for observed signals, named port connections, free-running clock generators, and $monitor for change-triggered logging
