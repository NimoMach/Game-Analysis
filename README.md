# Game-Analysis
In this Project I have done data analysis on game data using MySQL.
The Goal is to analyse the game dataset and find points which can improve the game.
### Dataset Description:
- The dataset contains two tables, Player details and Level details
- The player details contains all the details related to player
- The level details contains features which describes the levels in the game
- player_id is the primary key of player details table.
#### Player Dataset Description:
- `P_ID`: Player ID
- `PName`: Player Name
- `L1_status`: Level 1 Status
- `L2_status`: Level 2 Status
- `L1_code`: Systemgenerated Level 1 Code
- `L2_code`: Systemgenerated Level 2 Code
#### Level details dataset description:
- `P_ID`: Player ID
- `Dev_ID`: Device ID
- `start_time`: Start Time
- `stages_crossed`: Stages Crossed
- `level`: Game Level
- `difficulty`: Difficulty Level
- `kill_count`: Kill Count
- `headshots_count`: Headshots Count
- `score`: Player Score
- `lives_earned`: Extra Lives Earned
