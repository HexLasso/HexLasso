# Comparison of tools for static pattern discovery in binary data

## Overview

|| FF-16 | FF-16-TUI | FF-16-Web |
|-|-|-|-|
|Scope         | File layout analysis, bulk analysis       | Localized analysis, interactive analysis      | Localized analysis, interactive analysis      |
|Repository    | [Link](https://github.com/HexLasso/FF-16) | [Link](https://github.com/HexLasso/FF-16-TUI) | [Link](https://github.com/HexLasso/FF-16-Web) |
|Interface         | CLI                 | TUI                | Browser UI |
|Can run offline   | Yes                 | Yes                | Yes        |
|Can run without download | No           | No                 | [Yes](https://hexlasso.github.io/FF-16-Web) |
|Interactive       | No                  | Yes                | Yes        |
|Language          | Go                  | Go                 | HTML/JS    |


## Capabilities

|| FF-16 | FF-16-TUI | FF-16-Web |
|-|-|-|-|
|Dictionary                   | Yes                  | Yes                | No         |
|Max file size                | 16 MB                | 16 MB              | 4 MB       |
|Min gap                      | Configurable (0-127) |Configurable (0-127)| 0          |
|Max gap                      | Configurable (0-127) |Configurable (0-127)| 31         |
|Freq threshold               | Configurable (1-255) |Configurable (1-255)| No         |
|Pattern count per block      | 1                    | 10                 | 10         |
|Pattern filter               | Byte 00, Bit balance | No                 | No         |
|Pattern highlight in hexdump | No                   | Yes                | Yes        |
|Aggregate blocks into chunks | Yes                  | No                 | No         |
