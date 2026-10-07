# Wuhuan (Brian) Deng

**Applied Mathematics | Sports Analytics | Statistical Learning**

I am an applied mathematics researcher interested in using statistical learning, machine learning, and context-aware modeling to study decision-making and performance in sports.

<!-- Add your preferred public contact links below. -->
**Contact:** [Email](dwhbrian@163.com)

## Personal Background

**Ningbo Solvi** - AI Algorithm Engineer | Feb. 2026 - Now
**University of Washington** — M.S. in Applied and Computational Mathematics | Sep. 2024 - Dec. 2025  
**University of California, San Diego** — B.S. in Applied Mathematics | Sep. 2021 - Jun. 2024

## Research Interests

- Sports outcome forecasting
- On-field strategy and decision modeling
- Player performance evaluation
- Context-aware performance metrics
- Sports decision analytics
- Interpretable statistical learning
- Machine Learning

## Research & Projects

### NBA Three-Point Dependence

**Link:** [Repository](https://github.com/aryarksub/NBA_3PT_Dep)

- Develops a framework for measuring how strongly NBA players and teams depend on three-point shooting beyond attempt rate and scoring share.
- Studies behavioral dependence through counterfactual alternatives and structural preference through inverse reinforcement learning.
- Builds expected points model based on player tracking data: estimating shot-make probabilities and expected offensive value from spatial, defensive, player, and game-context features.
- Compares histogram-based gradient boosting, a player-embedding neural network, and a spatial-cluster model on a shared train-test split, with an emphasis on discrimination and probability calibration.

### Adjusted RBI and Contextual RBI

**Links:** [Paper](https://arxiv.org/abs/2511.19642) · [Repository](https://github.com/briandeng030216/adjusted_rbi)

- Introduces Adjusted Runs Batted In (ARBI) and Contextual Runs Batted In (CRBI), two context-aware baseball metrics.
- Constructs pre- and post-event Win Expectancy from inning, score, outs, and base-runner state, with interpolation and tail extensions for states outside the empirical table.
- Applies monotone weighting functions to changes in Win Expectancy, then adds terminal Win Expectancy to distinguish scoring events with similar impact but different game contexts.
- Compares the resulting ARBI and CRBI measures with traditional RBI and established offensive statistics.

### Discipline Score

**Links:** [Paper](https://arxiv.org/abs/2511.19672) · [Repository](https://github.com/briandeng030216/discipline_score)

- Develops a pitch-level framework for evaluating the quality of a hitter's swing decisions.
- Uses Statcast pitch location, velocity, movement, spin, count, handedness, and pitch type to model league-wide swing probability.
- Compares multilayer-perceptron and K-nearest-neighbor probability estimates using calibration curves and Brier scores.
- Converts predicted swing probability and the observed swing/take decision into Discipline Score, then explores an adjusted version incorporating exit velocity and launch angle.

### Sports Database

**Link:** [Repository](https://github.com/briandeng030216/sports_database)

- Provides reproducible Python pipelines for building local MLB, NBA, and NFL datasets.
- Retrieves team, game, player, play-by-play, pitch-level, and game-level statistics.
- Tracks incremental updates and data completeness for repeatable sports analytics workflows.

### Outfield Runner Advancement

**Link:** [Repository](https://github.com/briandeng030216/outfielder_runner_advancement)

- Models the probability that a baserunner advances after an outfield catch.
- Engineers physical timing features from catch location, throw distance, runner speed, throwing speed, and fielder movement.
- Evaluates advancement probabilities with Log Loss, Brier Score, ROC AUC, and calibration curves.
- Uses K-nearest neighbors to estimate the difficulty of comparable opportunities and calculates prevention above expectation for fielder evaluation.

### Tennis Winning Factors Across Court Surfaces

**Link:** [Article](https://wsb.wharton.upenn.edu/analyze-tennis-winning-factors-across-different-surfaces-by-utilizing-random-forest/)

- Builds separate Random Forest classifiers for grass, clay, and hard courts using point-by-point Grand Slam data aggregated into player-match features.
- Models match outcome from ten serving and playing indicators, including serve speed, ace and double-fault rates, first- and second-serve win rates, net success, winners, and unforced errors.
- Uses Mean Decrease in Impurity feature importance and partial-dependence analysis to explain how performance factors influence win probability on each surface.

### Analysis and Prediction of Soccer Games

**Link:** [Article](https://insight.piscomed.com/index.php/I-S/article/view/332)

- Analyzes the Kaggle European Soccer Database, covering matches across 11 European countries together with match events, team and player attributes, and bookmaker odds.
- Uses Poisson and Skellam distributions to examine goal and net-goal patterns and constructs offensive, defensive, possession, shot, and efficiency features.
- Compares Logistic Regression, Decision Tree, Random Forest, and a deep neural network for match-result classification.
- Examines feature importance across Europe's five major leagues to identify league-specific drivers of match outcomes.

### Baseball Pitch-Type Prediction with Transformers

- Applies sequence modeling and Transformer-based methods to predict pitch type.
- Represents previous pitches as an ordered sequence rather than independent observations.
- Uses attention-based Transformer modeling to learn how pitch history and game context inform the next pitch selection.
- Frames the task as multiclass classification across pitch types and evaluates whether sequential context improves prediction.
### NeuroCodec Compression

**Link:** [Repository](https://github.com/shlizee/NeuroAI)

- Applied VQ-VAE based neural network and implemented MLP & Con1d layers to compress time-series neural signal by optimizing commitment & reconstruct loss.

---

I am continuing to develop projects at the intersection of sports, statistics, and decision science. Links marked with placeholders will be updated as repositories and project pages become available.
