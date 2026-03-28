# India_ETFs

python strategy_stack_v2_india.py --mode allocate  --universe IndianETFList.txt --holdings holdings.csv --cash-ticker LIQUIDBEES.NS  --top-k 5  --hold-band 7  --benchmark-hurdle nifty --export-prefix indian_alloc

python strategy_stack_v2_india.py --mode backtest --universe IndianETF.txt --cash-ticker LIQUIDBEES.NS  --top-k 5  --hold-band 7  --benchmark-hurdle nifty  --start 2020-01-01  --end 2026-03-28  --export-prefix indian_backtest