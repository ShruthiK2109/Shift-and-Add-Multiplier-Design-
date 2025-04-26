# Shift-and-Add-Multiplier-Design-

![sam](https://github.com/user-attachments/assets/cbd143b4-a0c3-4fc6-8dc3-fc1bcbfddfc8)


Shift and Add Algorithm:

Multiplicand (A) : The number to be multiplied.

Multiplier (B): The binary number by which the multiplicand is to be multiplied.

Accumulator (C): Stores intermediate results during the process, initially set to zero.

Process:

1. Initialize the Accumulator (C) to zero when rst is high and load the Multiplicand (A) and Multiplier (B) when rst is low.
   
2. Interate over the bits of the Multiplier (B) from the least significant bit to the most significant bit.

3. For each bit of the multiplier:
   
i) If the bit is 1, shift the multiplicand by i times and add it to the accumulator value

ii) If the bit is 0, no operations are carried out.

4. After processing all the bits, the final result is stored in the accumulator (C).
