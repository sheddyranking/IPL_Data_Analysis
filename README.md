# IPL_Data_Analysis
IPL Data Analysis (Sport Case Study)

#### Problem Statement=> Indept Analysis of David Werner(Australian Batsman) Performance. 

Filter out where `batsman` equal to `David Werner`,store in a new `df`  you can now do a value count on `dismissal kind` and `plot`, also do some analysis on the `batsman runs` and `plot` as well.

##### Dismissal kind.
![dismissal_kind](https://user-images.githubusercontent.com/42388234/160950464-051777c2-9bea-48dd-aa69-1e00864a49e4.png)
##### Batsman runs.
![batsman_run](https://user-images.githubusercontent.com/42388234/160950466-fb3e5172-ba6a-43ff-aa08-e7ce02835b45.png)

#### Problem Statement=>  Score Distribution by Each and Average Teams by Innings

Abbreviate the `batting and bowling teams`, group the `match_id,inning,batting_team,total_runs` reset_index and drop the match_id, store in a new_df, group the `innings` and plot.
##### Inning1
![inning1](https://user-images.githubusercontent.com/42388234/161381214-ff7beb4a-737d-4d33-8eb8-98d6b5d1e96e.png)

##### Inning2
![inning2](https://user-images.githubusercontent.com/42388234/161381263-444a1344-7e1c-49e9-90bd-f4d6247095b3.png)


#### Problem Statement=> How many Teams Score more than 200?

group the `match_id,inning,batting_team,bowling teams,total_runs` reset_index and filter where score>=200  and plot the teams scores.
##### batting_team score>=200
![batting_team_higher_score](https://user-images.githubusercontent.com/42388234/161381296-be98232a-a436-42a7-8f9e-77262cce742f.png)

##### bowling_team score>=200
![bowling_team_higher_team](https://user-images.githubusercontent.com/42388234/161381294-a4203c42-f0f2-414a-af2a-6d1cb073a5c5.png)

#### Problem Statement=>  Batsman Comparison

 Do a `groupby` to return `batsman_runs`,`ball` played by each batmans,`4s` count by each batsman,`6s` count by each batsman `strike_rate`, `max_runs` and concate all in one table.
 
 
#### Problem Statement=> Top 10 Batsman

Sum the Grouped `batsman` and `batsman_runs` and sort the in decending order,filter the top 10 and plot.

##### Top 10 Batsman
![top10_batsman](https://user-images.githubusercontent.com/42388234/161406129-612a1362-9bb4-4025-a146-d67048646c22.png)
 
#### problem Statement  Top 10 individual Scores by batsman

 Do a groupby on `match_id`,`batsman`,`batting_team`,`batsman_runs`, and sum them, sort the values by the `batsman_runs` in decending order and return top 10 heads.
 
 #### problem Statement =>  Wicket Takers
 
 Analyses the `Dismissal_kind` and plot

##### Wicket Taker
![Wicket_taker](https://user-images.githubusercontent.com/42388234/161406130-791bbeb8-a453-4f56-a30c-db5378e9ea9e.png)


#### problem statement => Basic Analysis.(Matches Analysis)

a.`Total Matches played`.

 shape[0]

b.`Total Venus`.

uinque count lenght on the cities

c.`Total Teams`.

unique count length on the teams

d.`Most man of the match award`.

value count on player of the match

e.`Maxi. win by run`.

do a filter on win by runs max.

f.`highest win by wickets`.

do a filter on win by wickets max.

#### problem statement => Perform Analysis Across Seasons of IPL

a.`Toss Decision Across seasons`.

countplot on toss_decision.

![Toss_decision_across_seasons](https://user-images.githubusercontent.com/42388234/162228129-dc76c9d9-4978-4da6-b69e-459af9e56c22.png)


b.`max. Toss Winners`.

value counts on toss_winners and plot

![max_toss_winner](https://user-images.githubusercontent.com/42388234/162228289-8ada4d4f-1745-4272-b8fd-cb15fb06c8a0.png)


c.`Total Matches vs Wins for Teams`.

do value counts on matches played and match wins, merge the data and plot.

![matches_played_vs_matches_wins](https://user-images.githubusercontent.com/42388234/162228389-c0548c10-354a-4b2e-9dd3-43e9acfd29a8.png)


d.`Matches Played Across Each Season`.

countplot on season.

![matches_played _across _each _season](https://user-images.githubusercontent.com/42388234/162228497-46010db6-9bef-456b-8c4f-d4400b051304.png)


#### problem statement =>  Comparative Analysis of Teams

a.`Runs Across seasons`

Merge the deliveries and match df and do groupbby on the seasson on the bases of total_runs and plot.

![total_runs](https://user-images.githubusercontent.com/42388234/162228692-bc60f5b7-1a96-4a39-afd7-c6028f5ce372.png)


b.`Average Runs Per Match in Each Seasons`

group the season by id and concat with season df and plot.

![per_match_runs](https://user-images.githubusercontent.com/42388234/162228791-0eb80f3a-30fd-4c5c-a5d8-165524e94155.png)


c.`Most Lucky Grounds for Teams`

write a function to return the total number of wins by teams ans plot.

![MI_lucky](https://user-images.githubusercontent.com/42388234/162228900-981281eb-5ab1-4c46-8594-890c7c6b3fed.png)


d.`Comparison Between two Teams on the Basis of there Wins`

write a function to return the wins by each teams and plot.

 ![compare](https://user-images.githubusercontent.com/42388234/162228988-40c0a979-e1b1-49dd-be8c-72d4ae73e51c.png)

 
 
