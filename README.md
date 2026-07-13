# Redefining-Modern-NBA-Player-Positions-Through-Clustering-Analysis

## Overview

Traditionally, basketball positions are divided into five positions, including Point Guard, Shooting Guard, Small Forward, Power Forward, and Center. However, as basketball has evolved continuously, traditional basketball positions may not completely capture players' versatile skill sets. The objective of the project is to reclassify NBA players’ positions using clustering analysis to accurately reflect players' varied skill sets by grouping them based on their similarities. The project employed Hierarchical Agglomerative Clustering (HAC) to create eight clusters for NBA players in the 2025/26 regular season. 23 features regarding the key players’ statistics were used to train the clustering model, and Principal Component Analysis (PCA) was employed to reduce our 23 dimensions down to 10 principal components to avoid the curse of dimensionality. Last but not least, PCA and t-Distributed Stochastic Neighbour Embedding (t-SNE), were applied to visualise the clusters.

## Description of Clusters

Cluster 0: Primary playmakers and scorers, as they are superior on multiple statistics. Typically star players and team leaders of the team. High shot attempts and shots made indicate they have exceptional scoring abilities. High USG% indicates those players handle the ball extensively.  With low % of 2P FG Ast'd and % of 3P Ast'd, They tend to create their own shot opportunities. We call this position Ball Dominant Player.

##### Notable Player: Luka Dončić, Kevin Durant, James Harden, Jalen Brunson

Cluster 1: Those players are capable of scoring in multiple ways. Typically, the second or third scorers of the teams. Those players tended to make more shots in mid and long range. However, defense and rebounding are their weaknesses, as the statistics in other areas are below average. We call this position Secondary Playmakers.

##### Notable Player: Jaden McDaniels, Payton Pritchard, Desmond Bane, Derrick White

Cluster 2: Excel in the defensive side while most of the three-point shots were assisted and from the corner area. Higher than average STL indicates they were specialised in perimeter defence. We call this position 3-D Player.

##### Notable Player: OG Anunoby, Donte DiVincenzo, Royce O'Neale, Kris Dunn

Cluster 3: Centers or power forwards who typically play in the paint area. High shot attempts and percentage in close range or near the rim, proficient in rebounding and shot-blocking skills. They anchor the defence in the paint area, protect the rim, secure rebounds, and provide a physical presence in the paint on both offense and defensse. However, their shooting abilities are a weakness, and they seldom make shots out of the paint area of the court. We call this position Traditional Big Man.

##### Notable Player: Rudy Gobert, Jalen Duren, Deandre Ayton, Ivica Zubac

Cluster 4: Similar to Traditional Big Man on the defensive side but higher tendency on long-range shooting (% of 3P Ast'd and %3PA Corner). It helps create the spacing for the team’s offense and open up different scoring opportunities for the team. The versatile skills are more appropriate to modern basketball. We call this position Modern Two-Way Bigs.

##### Notable Player: Karl-Anthony Towns, Chet Holmgren, Evan Mobley, Donovan Clingan

Cluster 5: Those players exhibited higher-than-average performance on three-point shooting, including the quantities and accuracies. Also, they had significant higher tendency toward three-point shooting compared to other clusters. As a result, those players specialised in long-range shooting, indicating they can knock down the long-range shot consistently and providing spacing to the team. However, they were underperformed in other statistics. We call this position Pure Shooter.

##### Notable Player: Mikal Bridges, Duncan Robinson, Tim Hardaway Jr., A.J. Green

Cluster 6: It was typically the forward players with high ability to shoot from the long range. High attempts and shooting accuracy from the three-point line led to draw defenders out of the paint. Drawing defenders away from the basket helps create the spacing for the team’s offence and different scoring opportunities for the teammates. Also, they have above-average rebounding and rim protection abilities
We call this position Stretch Forward.

##### Notable Player: Myles Turner, Naz Reid, Josh Hart, Miles Bridges

Cluster 7: Possessing extremely high productivity and superstar-level playmaking ability (AST%: 23.84%, USG%: 24.42%). They are not adept at three-point shooting, but are extremely skilled at driving to the basket (high attempt percentages in 0-3 feet and 3-10 feet), drawing significant fouls. They don't rely on outside shooting, but rather on their powerful athleticism to penetrate the paint and score or create opportunities for teammates. We call this position Point Forward.

##### Notable Player: Scottie Barnes, Paolo Banchero, Julius Randle, Amen Thompson, Cooper Flagg
