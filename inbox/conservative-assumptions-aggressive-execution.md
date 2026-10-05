# Be conservative about assumptions, aggressive about execution

**Status:** Candidate

## Current wording

Planning and execution require different kinds of caution.

A common failure mode is to use one global "cautiousness" setting:

- too conservative about making necessary structural changes;
- too willing to invent missing details in order to keep moving.

The better rule is the inverse:

**Be conservative about assumptions; be aggressive about verified execution.**

Before acting, lock the truth source, invariants, and unknowns. Once those are known, execute decisively within the verified boundary.

---

# 中文

## 目前表述

規劃與執行需要的是不同種類的保守。

常見失敗是把「謹慎」當成一個全域參數：

- 對必要的結構性修改過度保守；
- 為了把任務做完，卻對缺失細節過度自行補全。

更好的規則恰好相反：

**對假設保守，對已驗證的執行激進。**

動手前先鎖定真相源、不可破壞條件與未知項；一旦邊界被確認，就在已驗證範圍內果斷施工。
