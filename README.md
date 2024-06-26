# Baseball-stat-calc
This Python script calculates various baseball statistics based on user input. It provides options to calculate Batting Average, Slugging Percentage, On-base Plus Slugging (OPS), or all three statistics together.

How to Use
Run the script.
Choose the statistic you want to calculate by entering the corresponding number.
Follow the prompts to input the required data, such as hits, singles, doubles, etc.
The script will calculate and display the chosen statistic(s).
Functions
calculate_batting_average(hits, at_bats): Calculates the batting average based on the number of hits and at-bats.
calculate_slugging_percentage(hits, singles, doubles, triples, home_runs, at_bats): Calculates the slugging percentage based on the number of hits, singles, doubles, triples, home runs, and at-bats.
calculate_on_base_percentage(hits, walks, hit_by_pitch, at_bats): Calculates the on-base percentage based on the number of hits, walks, hit by pitch, and at-bats.
calculate_ops(batting_average, on_base_percentage, slugging_percentage): Calculates the On-base Plus Slugging (OPS) based on the batting average, on-base percentage, and slugging percentage.
get_user_input(): Prompts the user to input the required data for calculations.
calculate_all_stats(hits, singles, doubles, triples, home_runs, at_bats, walks, hit_by_pitch): Calculates all three statistics (Batting Average, Slugging Percentage, OPS) based on the user input.
**Example Usage**

Baseball Statistics Calculator
----------------------------------
Choose the statistic you want to calculate:
1. Batting Average
2. Slugging Percentage
3. OPS
4. All Three Stats
Enter your choice (1/2/3/4): 4
Enter the total number of hits (singles, doubles, triples, home runs): 300
Enter the number of singles: 100
Enter the number of doubles: 100
Enter the number of triples: 50
Enter the number of home runs: 50
Enter the number of at-bats: 1000
Enter the number of walks: 10
Enter the number of times hit by pitch: 2

Batting Average: 0.300
Slugging Percentage: 0.650
OPS: 1.258
