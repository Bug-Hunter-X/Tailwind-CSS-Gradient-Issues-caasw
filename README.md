# Tailwind CSS Gradient Bug

This repository demonstrates a common issue encountered when using Tailwind CSS gradients.  The problem stems from incorrectly specifying the `from-` and `to-` colors or the gradient direction in the `bg-gradient-to-r` class.

## Bug Report

The provided code snippet shows how an improperly configured gradient can lead to unexpected results. The gradient might not appear at all, or it may appear distorted or with unexpected colors.

## Solution

The solution involves careful verification of the color values and gradient direction.  Ensure that you use valid Tailwind CSS color classes or hex codes. Double-check that the direction (`to-r`, `to-b`, etc.) aligns with your desired effect. 