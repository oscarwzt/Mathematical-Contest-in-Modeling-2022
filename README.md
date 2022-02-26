# Mathematical-Contest-in-Modeling-2022
For this year's MCM, out team chose Problem C to work on. The description of the problem is in this repository.

I would like to first identify the team member/contributors: Ethan Lee, Hanxi (Joanna) Wang, and myself Zetian (Oscar) Wan. Ethan and Joanna mainly worked on researching trading strategies and compiled everything into our submission paper. I implemented, tested, and visualized the strategies in code to identify the optimal one.

First, out team identified the problem: considering the transaction fee on gold and bitcoin, how to maximize the return from 9/11/2016 to 9/10/2021. 
More specifically, we did not treat this problem as computing the optimal portfolio but as such: 
given $1000 initial investment, make that number on 9/10/2021 as large as possible.
To summarize our strategy very briefly, we want to trade gold as few times as possible because the 1% transaction fee (buy and sell) is much greater than the average daily return of gold, and mainly foucs on trading bitcoin due to its high return.

Our methods and results are in the paper attached in this repository. Our code is also here. MCMT.ipynb is our "exploration code." Throughout the developing process, the code became very messy, so I created the "clean up" version or the final version, which is MCMF.ipynb.
