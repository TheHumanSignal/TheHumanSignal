# Experiment: Decoding Grayscale Blocks with Fibonacci Indexes

**Date:** 2025-06-23  
**Author:** The Human Signal Project  
**Title:** Fibonacci-Indexed Grayscale Message 01

---

## 🧪 Objective

To demonstrate a simple grayscale-to-ASCII encoding method based on selecting pixel brightness values from blocks located at Fibonacci positions in a 13-block horizontal grayscale gradient image.

---

## 🔢 Method

1. A 13-block grayscale image is created, where brightness increases gradually from left (dark) to right (bright).
2. Grayscale values (0–255) are extracted from the blocks at positions:
   - 2, 3, 5, 8, and 13  
   (These correspond to the first few Fibonacci numbers.)
3. Each grayscale value is directly mapped to an ASCII character.

---

## 🎯 Input Values (Grayscale to ASCII)

| Position | Grayscale Value | ASCII Char |
|----------|------------------|-------------|
| 2        | 72               | H           |
| 3        | 101              | e           |
| 5        | 108              | l           |
| 8        | 108              | l           |
| 13       | 111              | o           |

---

## 📬 Decoded Message

---

## 🧠 Notes

- The success of this decoding confirms the grayscale blocks were uniformly scaled and the Fibonacci-indexed sampling strategy is valid.
- This method can be reused in further experiments with altered patterns or different index functions (e.g., prime numbers, Lucas sequence, etc.).

---

## 🔗 Related Experiments

_To be added._

---

## 🧩 Keywords

`grayscale encoding`, `Fibonacci`, `ASCII message`, `image cipher`, `The Human Signal`, `AI-targeted encoding`, `visual code`
