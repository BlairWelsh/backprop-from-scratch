# backprop-from-scratch

Working through Andrej Karpathy's [micrograd](https://github.com/karpathy/micrograd) to understand neural networks and backpropagation from the ground up.

The goal is to understand what's actually happening when a neural network trains — not just conceptually, but in working code. micrograd builds a scalar-valued autograd engine and a small neural network library on top of it in around 150 lines of Python.

## Contents

| File / Folder | What it is |
|---|---|
| `micrograd/` | Karpathy's micrograd library — the source we're working from |
| `micrograd_lecture_first_half_roughly.ipynb` | Lecture notebook: building the Value class and autograd engine |
| `micrograd_lecture_second_half_roughly.ipynb` | Lecture notebook: building the neural network layer on top |

## Context

This follows on from working through 3Blue1Brown's neural network series (chapters 1–4), which covered the conceptual and mathematical side — what a neural network is, how gradient descent works, what backpropagation is doing, and why the chain rule matters. micrograd is where that becomes real code.

## Reference

- [karpathy/micrograd](https://github.com/karpathy/micrograd) — the original repo
- [The spelled-out intro to neural networks and backpropagation: building micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0) — Karpathy's lecture video
