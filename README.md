# ⚽ Machine Learning Project: Football Player & Team Data

## 📊 Dataset Overview
The dataset is composed of multiple tables covering players, teams, performances, market values, and transfers.  
Together, they allow us to analyze player careers and team dynamics from several perspectives.

The available dataframes are:

- **player_injured_df** → Records of player injuries, including dates and types.  
- **player_latest_market_value_df** → Latest known market value of each player.  
- **player_market_value_df** → Historical player market values across time.  
- **player_national_performances_df** → Player performances with national teams (caps, goals, etc.).  
- **player_performances_df** → Club-level performances such as matches, goals, assists.  
- **player_teammates_played_with_df** → Teammates each player has shared the field with.  
- **team_children_df** → Links between main clubs and their secondary or youth teams.  
- **team_competitions_seasons_df** → Teams’ participation in competitions by season.  
- **team_details_df** → General metadata about teams (name, country, founding year, etc.).  
- **transfer_history_path_df** → Player transfer history across clubs.


## 📂 Data Storage
The raw data is **not stored in this repository** (to keep it lightweight).  
Instead, all files live in **Google Drive**.

To ensure reproducibility, we provide a script (`download_data.py`) that downloads all necessary folders automatically.


## 📥 How to Acces the Data
1. Install requirements:
  u go to a new termina and write pip install gdown
2. run the (`download_data.py`) file 

