# Song Popularity Prediction Competition Scripts and subs

In this competition, you are supposed to predict the popularity of a song given features like acousticness, danceability, key, loudness, etc.

- [Competition LINK ](https://www.kaggle.com/c/song-popularity-prediction/overview) -Song Popularity Prediction Competition

## Notes after the competition
We finished at 68 after dropping 45 positions. We didn't drop as much as other top public LBs but after analysing our submissions I can say that it was overfitting and no issues with data as some people have been saying that.

One of my submission if selected would have been under top 25 and it was a single model with not much FE.

####  Key points-
Imputations worked well in the comp.
A simple xgb model would have been good enough for top 25.People using **n_estimators** dropped massive positions.
Conclusion
Only If I had been careful enough by not introducing a few subs in the ensemble with n_estimators we would have got a very solid rank.


