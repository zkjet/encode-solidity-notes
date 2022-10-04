# Encode.club Soildity Foundations Notes

<img src="https://miro.medium.com/max/320/1*_VZIGjpHOHaoAmNcApUQgA.jpeg" alt="drawing" width="" height="100"/>

[Solidity Docs](https://docs.soliditylang.org/en/v0.8.17/)

## Table of Contents


<details>
<summary>Introduction</summary>
Here's a starting point for collaborative notes for our Solidity class at Encode.
</details>

### [Terminology](https://github.com/zkjet/encode-solidity-notes/blob/main/terminology.md)
### [Links](https://github.com/zkjet/encode-solidity-notes/blob/main/links.md)
### 01
### 02
### 03
### 04
### 05
### 06
### 07
### 08
### 09
### 10

## Markdown CheatSheet
[Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet)

```solidity

// SPDX-License-Identifier: GPL-3.0
pragma solidity >=0.4.16 <0.9.0;

contract SimpleStorage {
    uint storedData;

    function set(uint x) public {
        storedData = x;
    }

    function get() public view returns (uint) {
        return storedData;
    }
}

```
## Resources
## Contributors