# Test

 
> # Q1
> # weighted mean
> weighted_earning_rate_1 <- (0.7*0.15 + 0.2*0.09 + 0.1*0.05)/(0.7 + 0.2 + 0.1)
> weighted_earning_rate_1
[1] 0.128
> 
> investment <- data.frame(weight=c(0.7, 0.2, 0.1), earning_rate=c(0.15, 0.09, 0.05))
> weighted_earning_rate_2 <- weighted.mean(investment$earning_rate, investment$weight)
> weighted_earning_rate_2
[1] 0.128
 



출처: https://rfriend.tistory.com/tag/가중평균 [R, Python 분석과 프로그래밍의 친구 (by R Friend)]