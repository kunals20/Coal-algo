# Coal-algo
This is a basic stepwise mathematical algorithm to make the coal blend cost effective while taking account of coal properties.




To determine the most efficient and cost-effective blend using the provided coal examples, we need to consider the desired coke qualities, coal properties, availability, and costs. We'll calculate the blend composition that optimizes coke quality while minimizing expenses.

Step 1: Define the requirements and assign weights
Let's assume that the desired qualities are as follows:

High strength: Weight = 4
Low reactivity: Weight = 3
Maximum fixed carbon content: Weight = 5
Low sulfur content: Weight = 2
These weights reflect the relative importance of each quality. You can adjust the weights based on your specific needs.

Step 2: Normalize the weights
Normalize the weights to add up to 1:
Total Weight = 4 + 3 + 5 + 2 = 14
Normalized Weight = Weight / Total Weight

Normalized Weights:
Strength: 4/14 ≈ 0.286
Reactivity: 3/14 ≈ 0.214
Fixed Carbon: 5/14 ≈ 0.357
Sulfur: 2/14 ≈ 0.143

Step 3: Calculate the quality score for each coal
For each coal, calculate the quality score based on its properties and the normalized weights. Multiply each normalized weight by the respective property value for each coal, and sum the results.

Quality Score for Coal A:
Strength Score = 0.286 * 60 = 17.16
Reactivity Score = 0.214 * 32 = 6.848
Fixed Carbon Score = 0.357 * 60 = 21.42
Sulfur Score = 0.143 * 0.5 = 0.0715
Total Quality Score = 17.16 + 6.848 + 21.42 + 0.0715 ≈ 45.4995

Repeat the calculation for the other coals:
Quality Score for Coal B:
Total Quality Score = 0.286 * 70 + 0.214 * 20 + 0.357 * 70 + 0.143 * 1.2

Quality Score for Coal C:
Total Quality Score = 0.286 * 55 + 0.214 * 28 + 0.357 * 55 + 0.143 * 0.8

Quality Score for Coal D:
Total Quality Score = 0.286 * 85 + 0.214 * 10 + 0.357 * 85 + 0.143 * 0.3

Step 4: Calculate the cost-adjusted quality score
To consider the cost factor, divide the total quality score of each coal by its respective cost per ton.

Cost-adjusted Quality Score for Coal A = Total Quality Score for Coal A / $80
Cost-adjusted Quality Score for Coal B = Total Quality Score for Coal B / $100
Cost-adjusted Quality Score for Coal C = Total Quality Score for Coal C / $85
Cost-adjusted Quality Score for Coal D = Total Quality Score for Coal D / $120

Step 5: Determine the optimal blend
Calculate the cost-adjusted quality score for different blend compositions to find the most efficient and cost-effective combination.

Let's consider three potential blend compositions and calculate their cost-adjusted quality scores:

Blend 1: 50% Coal A, 30% Coal B, 15% Coal C, 5% Coal D
Blend 2: 45% Coal A, 30% Coal B, 20% Coal C, 5% Coal D
Blend 3: 40% Coal A, 30% Coal B, 20% Coal C, 10% Coal D

Calculate the cost-adjusted quality score for each blend composition using the formulas from Step 4.

Finally, compare the cost-adjusted quality scores of the blends to determine which one offers the highest score. The blend with the highest score would be the most efficient and cost-effective option for producing coke.

