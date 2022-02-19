# Kickstarting with Excel

## Overview of Project
A collegue, Louise, wrote a play and has aspirations to launch to the public as a commercial venture. With limited personal capital to operationalize, she is interested launching a crowdfunding campaign to aquire funds. However, without much knowledge about crowdfunding process or track records of success, Louise is hesitent to use a crowdfunding campaign. After analyzing the various aspects of launching the play, Louise estimated that the budget needed would be about $10,000. To help make a decision about whether or not to attempt a crowdfunding campain to launch her play, Louise has asked for help understanding fundraising data.

### Purpose
The purouse of this analysis was to investigate Kickstarter crowdfunding data to gather insights and uncover potential factors that may have influence on the success of kickstarter fundraising campaigns. 

## Analysis and Challenges
This investigation saught to overview kickstarter data, and identify identify trends in kickstarter campains. 

### Description of data
To analyze trends in crowdfunding, Kickstarter campaign data was utilized. The data drew from campaigns that started as far back as May 17th, 2009 and extended to campaigns that started as recent as March 15, 2017.  A number of campaign variables were included in the dataset as outlined in Table 1. The Parent Category and Subcategory were broken out separately to further narrow the parameters of the investigation. 

Table 1. Data variables

        Variable
     -------------- 
          Name
          Blurb
          Goal
          Pledged
          Outcomes
          Country
          Currency
          Deadline
          Launched at
          Staff Pick
          Backers Count
          Spotlight
          Category and Subcategory
          Percentage funded
          Average donation

The outcomes of the kickstarters campaigns fell into four categories; successful, failed, canceled, or live. Table 2 highlights the total for each category as well as the breakdown for the top 5 countries of origin.


Table 2. Campaigns by outcome

      Country   Total    Succcessful   failed   canceled   live  
      ------- --------- ------------- -------  ---------- ------
       All       4114       2185        1530     349       50
      ------ ---------- ------------- -------- ----------- -----
      Top 5:
        US        3038      1651        1097     257       33
        GB         604       366         205      25        8
        CA         146        64          64      17        1
        AU          74        19          41      14        0
        DE          53        23          27       3        0


As Louse had a budget in mind for her play, the funding information for the campaigns were also analyzed. Table 3 highlights some descriptive statistics comparing campaign goals and actual amounts pledged towards those goals.

              Campaign Outcome
           Successful  |   Failed
             -------      --------
     Goal     $5,049       $10,591
     Mean     $3,000        $5,000
     Median

     Pledged     
     Mean     $5,602          $561
     Median   $3,168          $105


Of specific interest was the play Foresight from Great Britain 

     Name       Outcome        Goal     Pledged     Avg Donation     Backers     Start     End
     ------     ---------     ------    --------    ------------    --------     -----    -----
     Foresight   Successful   $2000     $2004           $177.88        17       4/22/16   5/13/16




### Analysis of Theater Outcomes Based on Launch Date


![Theater Outcomes by Launch Date](attachment:98beaf21-9364-452f-ac58-8a75cc23d800.png)


### Analysis of Outcomes Based on Goals

![Outcomes by Goals](https://raw.githubusercontent.com/agomoll/kickstarter-analysis/main/Outcomes_vs_Goals.png?token=GHSAT0AAAAAABQ6GJ27ND4KQ46IZO5KLYYSYQROZIA)


### Challenges and Difficulties Encountered
