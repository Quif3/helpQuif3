obviously make sure all the files are in the same dir in code 


open the account_menu.py file and run that in the terminal




add a stock

add 3 daily data entries

show chart

this should call matplotlib and create you a chart of the stock data for the days and stock information that you provided in the daily data


it gives you fucking examples


follow the exact examples or your going to get kicked in the nutz and have to restart



the problem i am having is after you show chart its saying 



  File "/home/quif3/CEIS150/stock_menu.py", line 221, in <module>
    main()
  File "/home/quif3/CEIS150/stock_menu.py", line 216, in main
    main_menu(stock_list)
  File "/home/quif3/CEIS150/stock_menu.py", line 204, in main_menu
    display_chart(stock_list)
  File "/home/quif3/CEIS150/stock_menu.py", line 162, in display_chart
    display_stock_chart(stock_list, current_stock.symbol)
  File "/home/quif3/CEIS150/stock_menu.py", line 140, in display_stock_chart
    plt.plot(date, price)
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/pyplot.py", line 3578, in plot
    return gca().plot(
           ^^^^^^^^^^^
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/axes/_axes.py", line 1723, in plot
    self.add_line(line)
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/axes/_base.py", line 2309, in add_line
    self._update_line_limits(line)
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/axes/_base.py", line 2332, in _update_line_limits
    path = line.get_path()
           ^^^^^^^^^^^^^^^
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/lines.py", line 1032, in get_path
    self.recache()
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/lines.py", line 669, in recache
    x = _to_unmasked_float_array(xconv).ravel()
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/quif3/CEIS150/lib/python3.11/site-packages/matplotlib/cbook.py", line 1345, in _to_unmasked_float_array
    return np.asarray(x, float)
           ^^^^^^^^^^^^^^^^^^^^
TypeError: float() argument must be a string or a real number, not 'DailyData'



