**What is AMFI?**<br/>
The Association of Mutual Funds in India (AMFI) is dedicated to developing the Indian Mutual Fund Industry on professional, healthy and ethical lines and to enhance and maintain standards in all areas with a view to protecting and promoting the interests of mutual funds and their unit holders.AMFI was incorporated on August 22, 1995, as a non-profit organisation. As of now, 45 Asset Management Companies that are registered with SEBI, are its members.

**What is NAV?**<br/>
The performance of a particular scheme of a Mutual Fund is denoted by Net Asset Value (NAV). In simple words, NAV is the market value of the securities held by the scheme. Mutual Funds invest the money collected from investors in securities markets. Since market value of securities changes every day, NAV of a scheme also varies on day to day basis. The NAV per unit is the market value of securities of a scheme divided by the total number of units of the scheme on any particular date.

**What does this code do?**<br/>
This code loads an existing file named 'MFs.xlsx'
This file has 2 sheets in it. First sheet is titled 'NAV'. The second sheet is titled 'Mutual Funds'.
Note: It is essential to have the sheet titled 'NAV' in the input file if one is running the code for the first time.
The code then takes the index and the sheet name of the 'NAV' sheet, deletes it and creates a new sheet with same index and name.
Then the code pulls the NAV data for all mutual funds directly from the AMFI website and appends it in the new sheet titled 'NAV'.
The URL for the same is - 'https://www.amfiindia.com/spages/NAVAll.txt'
Once completed, the file will be saved.
