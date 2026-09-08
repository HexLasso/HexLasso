# Comparison of tools for static pattern discovery in binary data

## A

|| FF-16 | FF-16-TUI | FF-16-Web |
|-|-|-|-|
|Interface     | CLI                 | TUI                | Browser UI |
|Runs offline  | Yes                 | Yes                | Yes        |
|Interactive   | No                  | Yes                | Yes        |
|Language      | Go                  | Go                 | HTML/JS    |
|Purpose       |                      |                    |            |

## Capabilities

|| FF-16 | FF-16-TUI | FF-16-Web |
|-|-|-|-|
|Dictionary     | Yes                 | Yes                | No         |
|Max file size  | 16 MB               | 16 MB              | 4 MB       |
|Min gap        | Configurable (0-127)|Configurable (0-127)| 0          |
|Max gap        | Configurable (0-127)|Configurable (0-127)| 31         |
|Freq threshold | Configurable (1-255)|Configurable (1-255)| No         |
|Pattern count per block | 1          | 10                 | 10         |
|PAttern filter | BitBalance, Byte 00 | No                 | No         |
|Pattern highlight in hexdump | No    | Yes                | Yes        |
|Aggregate blocks into chunks | Yes   | No                 | No         |
