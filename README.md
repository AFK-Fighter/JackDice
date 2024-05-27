JackDice Bot Usage Guide

Disclaimer
All forms of risk from using this application are your full responsibility. You can determine your own luck formula. This application was created so that you don't get too addicted to playing and are able to maintain your mental health. If you feel this application is not useful, please stop using this application immediately.

General Guidelines
1. This BOT application is specifically intended for the Dice game on the Jacksclub.io website, for other category games please visit youtube.com/@AFK-Fighter
2. The features in this application may develop over time and as contributors develop
3. This application was created using the Python programming language and requires a minimum of Python 3.12.3 to run this application

Configuration instructions
You can also see configuration instruction video on the youtube.com/@AFK-Fighter
Please open the "config.py.txt" file and fill in the data as needed then save it again and change the extension to "config.py"
1. Make sure the Jacksclub login "username" & "password" is correct
2. Don't forget to fill in the path "fileDataProfit" & "fileDataPO"
3. You can fill in more than 1 data for the variables "coin", "tabDataPO" and "profitFilter" separated by a comma (,)

Guide to PO formula file dataPO.xlsx
1. The existing formula is only an example. Please write your own formula for better results
2. You can use more than 1 formula tab name to be used in certain "profitFilter" conditions in the "config.py" file
3. "profitFilter" is generally used for recovery, and the next "profitFilter" sequence separated by a comma (,) is generally used for normal play after the previous game made a profit according to the provisions.
4. Please do your own research or please discuss with many people to increase your knowledge
5. Do not open ".xlsx" files while the application is running. This will cause error problems and the application will likely stop
6. Do not modify the .xlsx file while the application is running. You can copy-paste from your master .xlsx file to the PO formula directory to change the formula

Explanation of dataPO.xlsx code
1. The code in dataPO.xlsx is an abbreviation code for the column in the Dice Jacksclub.io game
- PO = Payout/Multiplier = float data type with 3 decimal digits
- BB = Base bet ~ float data type with 8 decimal digits
- RO = Roll Over/Under ~ 0 = fixed, 1 = random
- NOB = Number of Bets ~ integer data type
- SOP = Stop on Profit ~ float data type with 8 decimal digits
- SOL = Stop on Loss ~ float data type with 8 decimal digits
- MBA = Max Bet Amount ~ float data type with 8 decimal digits
- SOW = Stop on Wins ~ integer data type
- SOLS = Stop on Losses ~ integer data type
- OW = On Win ~ 0 = reset, 1 = decrease, 2 = increase
- OWP = On Win Percent ~ float data type with 2 decimal digits
- OL = On Loss ~ 0 = reset, 1 = decrease, 2 = increase
- OLP = On Loss Percent ~ float data type with 2 decimal digits

Guide to saving the final result of the game in a file with the format [coin_code]_[yyyy-mm-dd].xlsx
1. The saved results are the results after the game stops
2. If the game stops due to an application error or you force close the application, it is possible that the data will not be saved
3. Do not open .xlsx files directly while the application is running. This will cause an error problem and you can read instruction no.2
4. You can copy the .xlsx directory/file to another directory to open the .xlsx file. This is to prevent errors from occurring due to things like pointer no.3

If you have questions or other suggestions, please visit the official YouTube channel at youtube.com/@AFK-Fighter

Thank You

Regards,
AFK-Fighter