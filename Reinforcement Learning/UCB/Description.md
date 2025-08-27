# UCB Ad Selection (Multi-Armed Bandit)

This project demonstrates the **Upper Confidence Bound (UCB)** algorithm applied to the **Ad Selection Problem**.  
It simulates how to choose the best ad to display in order to maximize the total reward (clicks/conversions) over multiple rounds.

---

## 📌 Algorithm Explanation
- The problem is modeled as a **Multi-Armed Bandit** with `num_ads` arms.
- At each round:
  1. The algorithm calculates the **Upper Confidence Bound (UCB)** for each ad.
  2. Selects the ad with the highest UCB.
  3. Records the reward from the dataset.
  4. Updates the average reward and confidence interval for that ad.



