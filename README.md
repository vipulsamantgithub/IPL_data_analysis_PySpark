# 📌 Overview
This project focuses on analyzing bowling performance during the Powerplay overs (Overs 1–6) in the Indian Premier League (IPL) by leveraging PySpark and Spark SQL in a distributed computing environment on Databricks, with data stored in AWS S3. By processing millions of records efficiently, the project uncovers key patterns and identifies the most effective bowlers in the early phase of the game.

# 🎯 Objectives
• To identify bowlers with the best economy and wicket-taking ability during Powerplay overs.
• To leverage PySpark transformations and SQL queries for scalable and fast data analysis.
• To join and transform raw IPL datasets from multiple sources for a comprehensive view.
• To create a data-driven approach that could assist team analysts, selectors, and commentators in understanding early-game bowling trends.

# 💡 Key Insights
• Economical bowlers during Powerplay overs can significantly restrict a team’s scoring potential and increase pressure early on.
• Wicket-taking ability in the first six overs often dictates match momentum and team advantage.
• Certain bowlers consistently maintain a low average runs per ball while also picking crucial early wickets, proving their value as Powerplay specialists.

# 📊 Impact
• Delivered high-performance analytics using PySpark on Databricks, reducing processing time on large IPL datasets.
• Enabled role-based evaluation of bowlers for better team formation and strategic planning.
• Demonstrated how big data tools can provide valuable sports insights by combining performance metrics and historical trends.
• Project serves as a template for sports analytics, integrating advanced SQL logic with distributed processing.

# 🔍 Key Findings
• Extracted and filtered over-level data (over_id BETWEEN 1 AND 6) to isolate Powerplay deliveries.
• Joined ball_by_ball, player_match, and player datasets to map bowler IDs to names.
• Calculated:
  Average Runs Conceded per Ball using ROUND(AVG(runs_scored), 2)
  Total Wickets in Powerplay using conditional aggregation on bowler_wicket
• Sorted results to highlight bowlers with both low economy rates and high wickets during Powerplay.
• Discovered a set of bowlers who consistently outperformed others in the early overs — key players for T20 success.


