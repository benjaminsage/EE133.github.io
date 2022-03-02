<h1 align="center">
	Lab 1: Measuring “parasitic” properties of passive components with a VNA
</h1>

## Table of Contents
- [Authors](#authors)
- [Abstract](#abstract)
- [Introduction](#introduction)
- [Experimentsl Setup](#experimental-setup)
- [Measurements and Results](#measurements-and-results)
- [Discussion](#discussion)
- [Summary](#summary)

## Authors

Author: Benjamin Sage

Lab Partners: Marc Huerta and Devorah Simon

## Abstract

Passive components in electronics are devices which only receive energy to be manipulated, but need no power to operate. Three of these components - resistors, capacitors, and inductors - form the basis of circuit design and analysis. In this lab, we analyze these three components using a Vector Network Analyzer (VNA) to see where they deviate from their theoretical behavior in real life. This analysis gives rise to an important discovery known as self-resonant frequency.

## Introduction

There are three principle passive components in electronic circuit design and analysis:
- Resistor
- Capacitor
- Inductor

Their impedance formulas follow, with R standing for Resistor, C for Capacitor, and L for Inductor:

<img src="https://render.githubusercontent.com/render/math?math=Z_R = R" align="center">
<img src="https://render.githubusercontent.com/render/math?math=Z_C = \frac{-j}{\omega C}">
<img src="https://render.githubusercontent.com/render/math?math=Z_L = j \omega L">

These are, however, theoretical only. Every resistor, capacitor, and inductor, in real life, actually contains all three of these components. A real resistor actually has a theoretical resistor, capacitor, and inductor, as do real capacitors and inductors.

The additional theoretical components are known as **pararasitics**.

### Parasitics

All three real components contain all three theoretical components.

A real resistor has both leading and trailing resistance and inductance. It has an internal resistor and inductor as well, in addition to a parallel capacitor.

![](images/resistor-real.png)

**Figure 1: Model of a real resistor**

A real capacitor has leading and trailing resistors and inductors. It has an internal inductor and resistor, in addition to a parallel capacitor and resistor.

![](images/capacitor-real.png)

**Figure 2: Model of a real capacitor**

A real inductor has no leading and trailing parasitic components. It has an internal capacitor in parallel with a resistor and a parellel resistor and inductor.

![](images/inductor-real.png)

**Figure 3: Model of a real inductor**

## Experimental Setup

## Measurements and Results

## Discussion

## Summary
