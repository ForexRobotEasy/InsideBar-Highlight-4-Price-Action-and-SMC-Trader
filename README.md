# InsideBar Highlight 4 Price Action and SMC Trader ReadMe

This ReadMe file provides an overview of the code for the 'InsideBar Highlight 4 Price Action and SMC Trader' program. The code is intended to highlight inside bars on a chart and identify market trends using the SMC Trader algorithm. Please note that ForexRobotEasy is not the official developer of this product, but is showcasing a sample code that can work as described in the product.

## Input Parameters

The program allows for customization through the following input parameters:

- `insideBarColor`: Specifies the color of the highlighted inside bars on the chart. The default value is `clrRed`.
- `insideBarStyle`: Specifies the style of the highlighted inside bars on the chart. The default value is `STYLE_SOLID`.

## Global Variables

The program uses the following global variable:

- `insideBarFound`: A boolean variable that indicates whether an inside bar has been found on the chart.

## Custom Functions

The program includes the following custom functions:

### `IsInsideBar()`

This function is responsible for identifying inside bars on the chart. It should contain the necessary logic to determine if an inside bar is present. The function returns `true` if an inside bar is found and `false` otherwise.

### `HighlightInsideBar()`

This function is responsible for highlighting inside bars on the chart. It uses the input parameters `insideBarColor` and `insideBarStyle` to customize the style and color of the highlighted bars. If an inside bar is found, the function sets `insideBarFound` to `true`.

### `SMCTrader()`

This function implements the SMC Trader algorithm to identify market trends. It utilizes necessary algorithms and calculations to determine the trends in the market.

## Program Execution

The program follows the standard execution flow of an MQL4 program:

### `OnTick()`

This is the entry point of the program. It is called on every tick of the chart. The function checks if an inside bar is present using the `IsInsideBar()` function. If an inside bar is found, the `HighlightInsideBar()` function is called to highlight the bar on the chart. Afterward, the `SMCTrader()` function is called to identify market trends.

### `OnInit()`

This function is called during program initialization. It should include any necessary initialization steps. In this code, it simply prints a message to confirm successful initialization.

## Product Description

The 'InsideBar Highlight 4 Price Action and SMC Trader' program is a simplified forex tool designed to highlight inside bars on a chart and identify market trends using the SMC Trader algorithm. It provides customization options for the style and color of the highlighted inside bars. The program is developed by the Forex Robot Easy Team.

Please note that ForexRobotEasy is not the official developer of this product. We are showcasing a sample code that can work as described in the product. To find the official developer and access detailed reviews and trading results of this product, please visit [Forex Robot Easy - InsideBar Highlight 4 & SMC Trader Simplified Forex Tool Review](https://forexroboteasy.com/forex-robot-review/insidebar-highlight-4-smc-trader-simplified-forex-tool-review/). For more information and support, it is recommended to refer to the official developer using MQL5.
