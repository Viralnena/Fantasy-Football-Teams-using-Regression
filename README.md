# Fantasy-Football-Teams-using-Regression

Abstract - ​The performance of football players in English Premier League varies largely from season to season and for different teams. It is
evident that a method capable of forecasting and analysing the future of these players’ on-field antics shall assist the management to great
extent. In a simulated environment like Fantasy Premier League, enthusiasts from all over the world participate and manage the players
catalogue for the entire season. Due to the dynamic nature of points system, there is no known approach for the formulation of dream team.
This study aims to tackle this problem by using a hybrid of Autoregressive Integrated Moving Average (ARIMA) and Recurrent Neural
Networks (RNNs) for time series prediction of player points and subsequent maximisation of total points using Linear Programming (LPP).
Given the player points for the past three seasons, the predictions have been made for the current season by modelling differently for ARIMA
and RNN, and then creating an ensemble of the same. Prior to that, proper data preprocessing techniques were deployed to enhance the efficacy
of prepared model. Constraints on the types of players like goalkeepers, defenders, midfielders and forwards along with the total budget were
effectively optimised using LPP approach. The validation of the proposed team was done with the performance in ongoing season, where the
players outperformed as expected, and helped in strengthening the feasibility of the solution. Likewise, the proposed approach can be extended
to English Premier League by official managers on-field. 

## References

* https://arxiv.org/abs/1909.12938
* Han J, Kamber M, Pei J. Data Preprocessing. Data Mining Concepts and Techniques 2011; 83-124: Morgan Kauffman Publications.
* Shivani, K. S. Sandhu and A. Ramachandran Nair, "A Comparative Study of ARIMA and RNN for Short Term Wind Speed Forecasting," 2019 10th International Conference on Computing, Communication and Networking Technologies (ICCCNT), Kanpur, India, 2019, pp. 1-7, doi: 10.1109/ICCCNT45670.2019.8944466.
