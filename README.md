# Stock Price Explorer

Small thing that runs using Kweb. Runs on port 16097 by default.

Search for shares and get their current prices (15-min delay).

Uses the Yahoo Finance API to get stock quotes. Because of this, you need to add a suffix for most non-US stocks. For example, input VOLV-B.ST to get the share price for Volvo B.

For some reason it doesn't like it when you input a stock for the first time, pressing enter again fixes it though. Not sure why, it just doesn't grab the input properly or something.