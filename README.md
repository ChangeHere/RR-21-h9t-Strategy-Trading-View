========================
Script Name: RR-21-h9t Style - Fib Bounce + SMA/VWAP + T1-T5
========================

Important to know.  This hasn't really been tested yet.  Also you may need to adjust the fib levels.
Please understand this script is not proven, it is in test phase!!!

========================
What this script does
========================
This is a full trading strategy designed to automatically trade the exact style that user RR-21-h9t talks about in the live chat.
It watches for bounce opportunities (pullbacks to support) using Fibonacci retracement levels combined with VWAP and SMAs — exactly how RR calls his levels live (“bounce coming at 24308-321 on NQ”).
Core Logic (How it decides to trade)

========================
Fibonacci Retracement Levels
========================
Automatically finds the most recent swing low and swing high.
Draws the three most important Fib levels: 38.2%, 50%, and 61.8%.
These act as dynamic support zones for long bounces.

========================
Confluence with SMA & VWAP
========================
Plots SMA 21, SMA 50, and SMA 200 (the moving averages RR-21-h9t often mentions).
Plots VWAP (Volume Weighted Average Price) — one of his favorite magnets.
The strategy only takes a long entry when price reaches a Fib level or VWAP and starts turning up.

========================
Entry Rule
========================
When price touches the Fib 38.2%, 50%, or 61.8% level (or VWAP) from below and begins to bounce → the strategy goes Long.

========================
Multi-Target T1–T5 System
========================
Once in a trade, it automatically plots 5 take-profit levels (T1 through T5) based on ATR multiples (1×, 1.8×, 2.8×, 4×, 6× ATR).
Dynamic labels appear on the right side showing each target.
The label automatically changes to “✓Booked” when price hits that level (exactly like the OCS AI Trader screenshot you showed).

========================
Stats Table
========================
Displays live performance in the bottom-right corner:
Total Trades
T1 Wins
T1 Win Rate



Summary – What makes this script special

It directly mimics RR-21-h9t’s real-time level calling style (Fib + VWAP + SMA confluence).
It turns his manual calls into an automated strategy with clear entries and 5-step profit-taking.
Clean, professional visuals (horizontal target lines + booked labels + stats table).
Very close to the OCS AI Trader look you liked in the screenshot.

This is one of the cleanest and most practical scripts we’ve built together for NQ/ES futures.
