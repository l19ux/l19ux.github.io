---
layout: post
title: Strat & Beating $$\frac{1}{4}$$ Negative Marking
---

# Strategy

There are two main strategies that have a high success rate and are fairly popular. Decide which one suits you better:

1.  <small>GA (5m) – English (9-11m) – Reasoning (17-18m) – Math (26-27m)</small>
2.  <small>English (9-11m) – GK (5m) – Reasoning (17-18m) – Math (26-27m)</small>



# Tips

1.  Attempt every single question.

2.  No marking for review, Don't come back to questions. Enter all the answers you know and use your gut feeling for the ones you don't.

3.  Don't change your strategy midway through the exam, at any cost.



# Why a 100% Attempt Rate is Better

For any given question, the probability of success (guessing the correct answer) is <small>$$\frac{1}{4}$$</small>, and the probability of failure is<small> $$\frac{3}{4}$$</small>.

The probability of getting exactly 'r' successes in 100 questions is given by the binomial probability formula:  
<small>$$P(X=r) = \binom{100}{r} \left(\frac{1}{4}\right)^r \left(\frac{3}{4}\right)^{100-r}$$</small>

Using this, the probability of guessing exactly 25 questions correctly is:
<small>$$P(X=25) = \binom{100}{25} \left(\frac{1}{4}\right)^{25} \left(\frac{3}{4}\right)^{75} \approx 0.091 = 9\%$$</small>

The probability of guessing all 100 correctly is 
<small>$$P(X=100) \approx 6.22 \times 10^{-61},$$</small>
 and the probability of guessing all 100 wrong is 
<small>$$P(X=0) \approx 3.207 \times 10^{-13}$$</small>

This is a nice way to look at it, but what we've calculated here is the probability of getting *exactly* 25 correct. A more practical approach is to see what it takes to nullify the negative marking (a net-zero score from guessing). For that, you need at least <small>$$\frac{20}{100}$$</small> correct answers. To find the true probability of benefiting, you'd have to sum the probabilities of getting <small>$$20, 21, 22,..,100$$</small> questions correct.

Another thing to note is that this assumes a random<small> $$25\%$$</small> guess. In a real exam, you can often eliminate one or two options. If you can eliminate two options, your probability of being correct jumps to <small>$$50\%$$</small>. If you eliminate one, it becomes <small>$$33\%$$.</small> Lastly, there will be a few <small>$$\approx 6-8$$</small> questions requiring a completely blind guess. The binomial probability formula shown above applies best to those. Based on my experiences and calculations, this strategy works. This is the mathematical clarification for what I meant by achieving a net positive delta. Cheers!
