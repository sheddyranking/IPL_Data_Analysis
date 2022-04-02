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
