# 'Inaam' The Search Tool for National Savings of Pakistan Prize Bonds (Unofficial)

Disclaimer
----
- This *'Prize Bond Search'* program hereinafter referred to as *Inaam* is provided for the sole purpose of convenience of prize bond search and does not represent *National Savings of Pakistan*.
- Draw results come from [National Savings of Pakistan][nsp] website and developer of the *Inaam* does not guarantee a positive result and shall not be held responsible for any false result. Users of the *Inaam* are required to confirm their results with *National Savings of Pakistan*.
- The *Inaam* does not constitute an offer to sell or trade, a solicitation to buy, or recommendation for any product of *National Savings of Pakistan*.
- The *Inaam* is for information purposes only and shall not be used for business purposes without permission.
----

The *Inaam* can be used to search for prize bond draw results against your bond number.

# Usage
1. Open the folder where you downloaded the `Inaam.exe` program. Double click to run it and it will prompt as follows
    ```sh
    Enter Amount:
    ```
2. Enter amount of your prize bond e.g. 100. Valid entries are Rs. 100, 200, 750, 1500, 7500, 15000, 25000 and 40000.
    ```sh
    Enter Amount:100
    Enter Prize Bond Number:
    ```
3. Enter the 6 digit number of your prize bond e.g. 588349.
    ```sh
    Enter Amount:100
    Enter Prize Bond Number:588349
    ```
3. Press enter and search will start. It will look for latest draw results in the same directory as your `Inaam.exe`program and download them if needed. (Results are already downloaded in the example below.)
    ```sh
    Enter Amount:100
    Enter Prize Bond Number:588349
    Searching...
    1  result found! :)
    Show details? y/n:
    ```
3. If you wish to see the results press `y` or press `n` to exit.
    ```sh
    Enter Amount:100
    Enter Prize Bond Number:588349
    Searching...
    1  result found! :)
    Show details? y/n:y
    -------------------------Draw Details-------------------------
    DRAW OF Rs.100
    Date: 15/08/2017
    HELD AT Karachi				
    Prize Amount: Rs. 700,000/
    --------------------------------------------------------------
    Search again? (y/n):
    ```

License
----

*Free Tool!*

   [nsp]: <http://savings.gov.pk/>
   [requests]: <https://pypi.org/project/requests/2.12.1/>
