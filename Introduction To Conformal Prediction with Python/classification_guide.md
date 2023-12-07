# Classification guide

- Fixed size predictions sets $\rightarrow$ Topk method
- Don't care about conditional coverage $\rightarrow$ Score method
- You dont care about conditional coverage as long as coverage **per group** is guaranteed
  - If you have enough data per group $\rightarrow$ Group balanced conformal prediction
  - If you dont have enough data $\rightarrow$ APS or RAPS
- You dont care about conditional coverage as long as each class has guaranteed coverage $\rightarrow$ Class conditional conformal prediction
- You dont care about conditional coverage in general
  - Not to many classes $\rightarrow$ APS
  - Too many classes (like imagenet) $\rightarrow$ RAPS 