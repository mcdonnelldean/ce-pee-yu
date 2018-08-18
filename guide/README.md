# Cee Pee Yu

Cee Pee Yu is a Modular PCB based 8-Bit CPU Study. It follows Ben Eater's, [Build an 8-Bit Computer][], reference design as it's basis.

The primary differentiation is the fact that Cee Pee Yu is not built on a series of bread boards, rather, it is composed of a number of custom designed PCB boards. Besides this, there are minor additions and changes to make the project more compatible with PCB Format.


## Who is this for
As a study, this resource is primarily for the benefit of the author. However, the point of this study is to clearly and deeply work through the process of building a CPU; and in that regard, it should be easy to follow for anyone with sufficient interest.

It is important to note, since Cee Pee Yu is a living study, it is likely to be wrong, incomplete, and missing key info in a number of places. I want to explicitly call this out at the outset because my time available to work on Cee Pee Yu will be bursty.

## What is the end goal
The ideal end state for Cee Pee Yu, is a modular set of 'parts' that can be put together to form different sorts of simple CPU's. In terms of complexity the hope is to eventually be able to run very simple C code (likely enough to compute the fibonacci sequence).

## Table of Contents
* Getting started
  * [Project overview](/guide/introduction.md)
  * [Where to buy parts](/guide/where-to-buy-parts.md)
  * [Print your own boards](/guide/print-your-own-boards.md)
* Modules
  * [Oscillator A](/guide/oscillator-a.md)
  * [Oscillator B](/guide/oscillator-b.md)
  * [Clock Controller](/guide/clock.md)
  * [Power and Signal Bus](/guide/signal-bus.md)
  * [Bus Indicator](/guide/bus-indicator.md)
  * [Register A](/guide/register-a.md)
  * [Register B](/guide/register-b.md)
  * [Register IR](/guide/register-ir.md)
  * [Arithmetic and Logic Unit](/guide/arithmetic-and-logic-unit.md)
  * [Random Access Memory](/guide/random-access-memory.md)
  * [Program Counter](/guide/program-counter.md)
  * [Seven Segment Output](/guide/seven-segment-output.md)
* Tools
  * [EEPROM Programmer](/eeprom-programmer.md)


  [Build an 8-Bit Computer]: https://eater.net/
