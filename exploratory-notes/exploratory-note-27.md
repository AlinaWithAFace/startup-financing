Exploratory Note 27

Valuing Real Options with the Binomial Options Pricing Model

**INTRODUCTION**

At this point, the logic of real options should be obvious, but can we
actually quantify their value? Thanks to advancements in the pricing of
contingent claims made several decades ago, we can with the help of
option pricing models. This second exploratory note of the evening
broadly considers the value of flexibility, examines the variables which
impact the value of real options, and presents an in-depth mathematical
example that illustrates the use of the binomial options pricing model.

**THE VALUE OF FLEXIBILITY**

Projects with embedded real options are inherently more flexible.
Consider the following chart:

![](media/image1.emf){width="3.3454800962379703in"
height="6.652653105861767in"}

Is flexibility most valuable under conditions of certainty or
uncertainty? Why?

For a project with a very high NPV, is flexibility likely to be a
deciding factor?

What about for a project with a very low NPV? In such a case, is
flexibility likely to be a deciding factor?

For what projects then does the value of flexibility likely matter the
most?

**THE VARIABLES OF CONCERN**

In option pricing, there are five variables of significant concern: the
value of the underlying risky asset or project; the exercise price of
the option; the time to expiration of the option; the standard deviation
of the value of the underlying asset or project; and, finally, the
risk-free rate of interest over the life of the option.

***The Value of the Underlying Risky Asset or Project***

The value of options is in large part derived from the value of the
underlying risky asset or project. Is the relationship direct or
inverse? Why?

So, an increase in the present value of a project will increase the NPV
(without flexibility) and therefore the ROA will also increase? Is this
correct?

***The Option Exercise Price***

What is the exercise price of a real option? Why does it matter?

What is the relationship between option exercise price and project
value?

***The Time to Expiration of the Option***

What is the relationship between project value and the time to
expiration of a real option?

All other things being equal, if a real option expires in a month, will
it be worth more or less than if it expired in one year? In ten years?
Why?

***The Standard Deviation of the Value of the Underlying Asset***

Assume that you are considering buying the rights to mineral deposits
which are filled with gold, but which could only be exploited at a cost
of \$2,000 per ounce. Today, the price of gold is roughly \$1,100. If
the standard deviation in the price of gold is very modest, would such
an investment likely generate a solid return? What if the standard
deviation is extreme?

***The Risk-Free Rate of Interest over the Life of the Option***

An increase in the risk-free rate will increase ROA since it will
increase the time value of money advantage in deferring the investment
cause.

**THE BINOMIAL OPTIONS PRICING MODEL**

The most intuitive option pricing model available is the binomial
options pricing model. The derivation of the model is unnecessary for
this course, but the mechanics are pretty straightforward and best
illustrated through an example. Consider the three-phase construction
project below:

> Three Phase Decision
>
> Year 1 -- Design Phase -- \$200
>
> Year 2 -- Engineering Phase -- \$300
>
> Year 3 -- Final Construction Phase -- \$700
>
> Present Value of Cash Flows -- \$1000
>
> Net Cash Flows (Years 4-15) -- \$178
>
> WACC = 10%
>
> NPV = -\$51.2
>
> u = 1.5 ; d = 1/u = .67 ; q = .46
>
> C~t~ = \[qC~u,t+1~ + (1-q)C~d,t+1~\]/1+WACC

What flexibility is inherent to this project? Where are the decision
points?

![](media/image2.emf){width="5.177083333333333in"
height="3.3834765966754157in"}

Given the expected present value of the positive cash flows (\$1,000)
and the up and down jumps (1.5; .67), our value tree looks like this:

![](media/image3.emf){width="5.0625in" height="3.382794181977253in"}

How accurate is this type of mathematics likely to be?

Using these value estimates, we then work backwards and calculate the
option values for the real option (to invest or abandon the project) at
the beginning of the third period using C~t~ = \[qC~u,t+1~ +
(1-q)C~d,t+1~\]/1+WACC.

![](media/image4.emf){width="4.875in" height="2.945945975503062in"}

Options never have a value less than zero. Why?

If the option value at t-2 is less than the exercise price at t-2,
should the investment be made or should the project be abandoned? Why?

Once the options at that stage have been priced, the decisions at the
beginning of the second period are addressed the same way; however, note
that the net cash flows from the first round of option pricing are now
utilized in the value tree.

![](media/image5.emf){width="3.8333333333333335in"
height="2.7971073928258967in"}

And then once more for the initial decision:

![](media/image6.emf){width="3.8541666666666665in"
height="3.2023906386701664in"}

The NPV of the project is -\$51.2; however, the ROA is \$87. In other
words, the uncertainty of the cash flows mixed with the flexibility to
abandon the project added \$138.2 in perceived value upfront!

Any concerns with this approach to the mathematics?

**CONCLUSIONS**

ROA is an incredibly powerful tool for capital budgeting decision
making. Even if the mathematics is overly burdensome for most, the logic
of real options should become second nature to practitioners.
