---
layout: default
title: Oceandrift
---

# Oceandrift D-Man collection

by Elias A. Batek ([@0xEAB](https://github.com/0xEAB)).  
License: [CC-BY-4.0](./COPYING.txt).


## Contract Programming

*2024-08-25*

[Contract programming](https://dlang.org/spec/contracts.html) is a nice and powerful feature.

<div class="gallery big">
  <img
    src="{{ site.baseurl }}/oceandrift/2024-08-25_contract-programming/d-man_contract-programming.svg"
    alt="Comic Strip: Contract Programming"
  >
</div>

But like with every tool it’s important to use it for the right job.
If one finds themselves in a situation where contracts verify whether input has been properly validated,
it might be better to replace those contracts with input validation.
This can not only save maintenance time spent keeping validation in sync with the contracts
but also prevent those application crashes that go hand in hand with failed contract assertions.
As crashes are bad for availability, they can end up becoming denial-of-service security vulnerabilities.
Keep in mind that availability is a security criterion similar to confidentiality and integrity.

[→ Source file](./2024-08-25_contract-programming/d-man_contract-programming.inkscape.svg)

### Sketch of panel 1 (Bonus)

<div class="gallery">
  <img
    src="{{ site.baseurl }}/oceandrift/2024-08-25_contract-programming/d-man_contract-programming_sketch.png"
    alt="Sketch of panel 1 of the Contract Programming comic strip"
  >
</div>


## Ship

*2024-07-21*

Created for the “dlang-dockerized” project to be used as its avatar.

Note: `d-man_cargo-ship.svg` is an Inkscape-SVG file.
You might want to reduce it to plain SVG for further use.

The original sketch was drawn using the “Simple Draw” app on my phone.
It’s included here as a bonus (`d-man_ship-sketch.svg`).

<div class="gallery">
  <img
    src="{{ site.baseurl }}/oceandrift/2024-07-21_ship/d-man_cargo-ship.svg"
    alt="D Man on a cargo ship"
    class="big"
  >
  <img
    src="{{ site.baseurl }}/oceandrift/2024-07-21_ship/d-man_ship-draft.svg"
    alt="Draft: D Man on a cargo ship"
    class="big"
  >
  <img
    src="{{ site.baseurl }}/oceandrift/2024-07-21_ship/d-man_ship-sketch.svg"
    alt="Sketch: D Man on a cargo ship"
    class="big"
  >
</div>
