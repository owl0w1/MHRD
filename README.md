# MHRD Solutions
Solutions to the CPU design game [MHRD](https://store.steampowered.com/app/576030/MHRD/).

All solutions expect RAM4W16B, DECODER, and CPU are optimal (w.r.t. the number of NAND gates used):
- RAM4W16B: This can be improved because the automatically generated MUX16B and REGISTER16B are not optimal. However, expanding out the optimal MUX16B and REGISTER16B might exceed the 39*82 character limit.
- DECODER: There is a 11 NANDs solution on the leaderboard, but it is unclear whether it cheats the test cases.
- CPU: The CPU uses the automatically generated REGISTER16B, so by extension it is not optimal.
