
| Pin#  | Pin Name     | Function PINSEL = 0                                       | Function PINSEL = 1 | Input/Output        |
| ----- | ------------ | --------------------------------------------------------- | ------------------- | ------------------- |
| 1     | VDDINT_1     | Internal stack voltage reference pin                      |                     | Output              |
| 2-8   | VDD          | VDD supply                                                |                     | Input               |
| 9     | TDO          | JTAG OUTPUT                                               |                     | Output              |
| 10    | TDI          | JTAG DATA IN                                              |                     | Input               |
| 11    | TCK          | JTAG CLOCK                                                |                     | Input-Clock         |
| 12    | VDDINT_2     | Internal stack voltage reference pin                      |                     | Output              |
| 13    | RSVD         | Reserved                                                  |                     | Output              |
| 14    | VSS          | Ground                                                    |                     | Input               |
| 15    | TRIP_RX_OUT  | TRIP_OUT                                                  | RX_OUT              | Output              |
| 16    | TX_RESET_OUT | UART_TX_OUT                                               | RESET_OUT           | Output              |
| 17    | RESET_TX_IN  | RESET_IN                                                  | UART_TX_IN          | Input with pull-up  |
| 18    | RX_TRIP_IN   | UART_RX_IN                                                | TRIP_IN             | Input with pull-up  |
| 19    | VDDIO        | IO Voltage Rail                                           |                     |                     |
| 20    | REFCLKOUT2   | Ref clock from ASIC to next ASIC. Pin muxed in Debug Mode |                     | Input, no pull      |
| 21-28 | VSS          | Ground                                                    |                     | Input               |
| 29    | REFCLKIN     | Ref clock for ASIC                                        |                     | Input               |
| 30    | VDDIO        | IO Voltage Rail                                           |                     | Input-Output        |
| 31    | RX_TRIP_OUT  | UART_RX_OUT                                               | TRIP_OUT            | Output              |
| 32    | RESET_TX_OUT | RESET_OUT                                                 | UART_TX_OUT         | Output              |
| 33    | TX_RESET_IN  | UART_TX_IN                                                | RESET_IN            | Input with pull-up  |
| 34    | TRIP_RX_IN   | TRIP_IN                                                   | UART_RX_IN          | HI-Z with pull-down |
| 35    | VSS          | Ground                                                    |                     | Input               |
| 36    | PINSEL       | Select data pin function                                  |                     | Input with Pull-up  |
| 37    | RSVD         | Reserved                                                  |                     | Output              |
| 38    | REFCLKOUT1   | Ref clock from ASIC to next ASIC. Pin muxed in Debug Mode |                     | Output              |
| 39    | TMS          | JTAG Mode Select                                          |                     | Input               |
| 40    | TRST         | JTAG RESET                                                |                     | Input               |
| 41-42 | VDD          | VDD Supply                                                |                     | Input               |
| 43-48 | VSS          | Ground                                                    |                     | Input               |
| 49-52 | VDD          | VDD Supply                                                |                     | Input               |
| 53-58 | VSS          | Ground                                                    |                     | Input               |
| 59-60 | VDD          | VDD Supply                                                |                     | Input               |
