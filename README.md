# 1-Byte-Memory
A fully working 1 Byte Memory , handcrafted from scratch using 2N2222 BJTs ⚙️

🛠️ Here’s how the journey went:

 → Started by building basic gates — NOT, NAND, NOR — using NPN transistors
 → Combined NANDs to form a SR Latch
 → Added clock control to make a SR Flip-Flop
 → Modified SR Flipflop to make a D Flip-Flop and could have stopped at D-Flipflop but ...
 →Tried to add feedback for JK logic... and then things broke ....
 → Introduced RC delays to fix timing issues , It worked like a charm 💥 — full JK Flip-Flop with proper toggling!
→ Now for memory I used D flipflops 8 times to get 8 independent bits memory .
