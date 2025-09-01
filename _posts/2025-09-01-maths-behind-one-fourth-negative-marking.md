---
layout: post
title: Strat & Beating \(\frac{1}{4}\) Negative Marking.
---

# Strat
There are mainly 2 strategies that have a high success rate and are fairly popular, decide which suits you better:
    
1. GA (5 mins) - English (9-11 mins) - Reasoning (17-18 mins) - Math (26-27 mins)
    
2. English (9-11 mins) - GK (5 mins) - Reasoning (17-18 mins) - Math (26-27 mins)

# Tips 
1. Attempt every single question.

2. No marking for review/coming back to a question - feed in all answers you know and use gut feeling (first thought) for ones you don't know about.

3. Don't change strategy midway into the exam, at any cost.

# Why a 100% attempt rate is better

For any given question, the probability of success (guessing the correct answer) is \(\frac{1}{4}\), and the probability of failure is \(\frac{3}{4}\).

The probability of getting exactly 'r' number of successes in 100 questions is given by the binomial probability formula:
$$P(X=r) = \binom{100}{r} \left(\frac{1}{4}\right)^r \left(\frac{3}{4}\right)^{100-r}$$

Using this, the probability of guessing exactly 25 questions correctly is:
$$P(X=25) = \binom{100}{25} \left(\frac{1}{4}\right)^{25} \left(\frac{3}{4}\right)^{75} \approx 0.091 = 9\%$$

The probability of guessing all 100 correctly is \(P(X=100) \approx 6.22 \times 10^{-61}\), and the probability of guessing all 100 wrong is \(P(X=0) \approx 3.207 \times 10^{-13}\).

This is a nice way to look at it, but what we've calculated here is the probability of getting *exactly* 25 correct. A more practical approach is to see what it takes to nullify the negative marking (a net-zero score from guessing). For that, we need at least \(\frac{20}{100}\) correct answers. To find the true probability of benefiting, we'd have to sum the probabilities of getting \(20, 21, 22, \dots, 100\) questions correct.

Another thing to note is that this assumes a random \(25\%\) guess. In a real exam, you can often eliminate one or two options. If you can eliminate two options, your probability of being correct jumps to \(50\%\). If you eliminate one, it becomes \(33\%\).

Lastly, there would be a few (\(\approx 6-8\)) questions requiring a completely blind guess. The binomial probability formula shown above applies best to those. Based on my experiences and calculations, this strategy works. This is the mathematical clarification for what I meant by achieving a net-positive delta. :) Cheers!
