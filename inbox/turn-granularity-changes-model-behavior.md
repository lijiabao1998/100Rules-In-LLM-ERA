# Turn granularity changes model behavior

**Status:** Candidate

## Current wording

Conversational granularity affects reasoning quality.

When a complex problem arrives one sentence at a time, the model is pushed toward local optimization: resolve the latest ambiguity, patch the newest branch, and react to the most recent wording.

When the same problem arrives as a coherent block, the model can optimize globally: identify the main objective, separate signal from noise, compare hypotheses, compress repeated context, and produce a more stable overall model.

For complex analysis, use fine-grained turns for correction and probing, but periodically switch to batch synthesis.

---

# 中文

## 目前表述

對話粒度會改變推理品質。

當複雜問題一句一句輸入時，模型容易被推向局部最優：處理最新歧義、修補最新分支、回應最近一句話。

同一批資訊如果以完整區塊輸入，模型就更容易做全域最佳化：辨識主目標、分離訊號與噪音、比較競爭假設、壓縮重複背景，並產出更穩定的整體模型。

因此複雜分析適合用細粒度對話做校正與探針，但應定期切回整批綜合。
