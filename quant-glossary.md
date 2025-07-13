# 📖 Quant Finance Glossary

This glossary contains brief definitions and explanations of key concepts in quantitative finance, in the context of my learning plan.

---

## Table of contents
- [A](#a)
- [B](#b)
- [C](#c)
- [D](#d)
- [E](#e)
- [F](#f)
- [G](#g)
- [I](#i)
- [L](#l)
- [M](#m)
- [N](#n)
- [O](#o)
- [P](#p)
- [R](#r)
- [S](#s)
- [T](#t)
- [V](#v)
- [Y](#y)

---

## A

### Alpha
> Measure of the performance of an investment strategy in excess of the expected return for its level of risk (generally measured by beta).

### Arbitrage
> Strategy that seeks to profit without risk by taking advantage of price differences between markets.

### Appreciation
> A positive growth.

### Average Annual Return
> The annual return on an investment.
> The correct way of calculating the average annual return is to use a [geometric average return](#geometric-average-return):

$$
\begin{equation}
i = \sqrt[N]{\frac{FV}{PV}} - 1
\end{equation}
$$

$$
\begin{equation}
i = \sqrt[N]{\sum_{j=1}^{N} 1 + i_j} - 1
\end{equation}
$$

> Also known as: **Average annual interest rate**, **Compound average annual return** and **True return**.

> [See also: Return](#return)

### Annual Percentage Rate (APR)
> Nominal annual rate for a compound interest. ???
> It handles situations in which there is compounding more frequently than once a year.

> **Note**: The investment's value increases at a faster rate with the increased frequency of compounding.

> [See also: Compound Interest](#compound-interest)

### Annuities
> A **series of cash flows** of **equal amount**, occurring at **even intervals**. 
> Evaluate a series of level cash flows - each cash flow is the same amount as the others - received at regular intervals.
$$
\begin{equation}
\begin{aligned}
FV &= \sum_{t = 1}^{N} {CF (1 + i)^{N - t}} \\
&= CF \sum_{t = 1}^{N} (1 + i)^{N - t}
\end{aligned}
\end{equation}
$$
$$
\begin{equation}
FV = CF \frac{(1 + i)^N - 1}{i}
\end{equation}
$$
> $t$: time period corresponding to a particular cash flow.

> This equation tells us that the **future value** of a **level series of cash flows**, occurring at **regular intervals** **beginning one period from today**, is equal to the amount **of cash flows multiplied** by the **sum of the compound factors**.

> The equation for the present value of a series of level cash flows beginning after one period simplifies to:
$$
\begin{equation}
\begin{aligned}
PV &= \sum_{t = 1}^{N} {CF \left( \frac{1}{(1 + i)} \right)^t} \\
&= CF \sum_{t = 1}^{N} \left( \frac{1}{(1 + i)} \right)^t \\
&= CF \sum_{t = 1}^{N} \frac{1}{(1 + i)^t}
\end{aligned}
\end{equation}
$$
$$
\begin{equation}
\begin{aligned}
PV &= CF \frac{1 - \frac{1}{(1 + i)^N}}{i} \\
&= CF \frac{(1 + i)^N - 1}{i (1 + i)^N}
\end{aligned}
\end{equation}
$$
> This equations tells us that the **present value** of an **annuity** is equal to the **amount of one cash flow multiplied** by the **sum of the discount factors**.

> These equations are examples of [ordinary annuities](#ordinary-annuity).

> [See also: Future value annuity factor](#future-value-annuity-factor).
> [See also: Present value annuity factor](#present-value-annuity-factor).

[Go to: Table of contents](#table-of-contents)

---

## B

### Backtesting
> Proceso de probar un modelo o estrategia usando datos históricos para evaluar su desempeño.

### Beta
> Medida de la sensibilidad de un activo o cartera frente a los movimientos del mercado.

### Balance
> 

### Basic Valuation Factor
> [Future Value](#future-value) with [Compound Interest](#compound-interest):
$$
\begin{equation}
FV = PV (1 + i)^N
\end{equation}
$$
- $N$: **number of compounding periods**.
- $(1 + i)^N$: **[Compound Factor](#compound-factor)**.

---

## C

### Credit Default Swap (CDS)
> 

### Company's financial strategic plan
> Framework of achieving its goal of maximizing shareholder wealth.

> Requires both long-term and short-term financial planning that brings together forecasts of the company's sales with financing and investment decision-making.

### Capital Structure of a Firm
> Mix of **debt** and **equity** that management elects to raise in funding itself.

### Capital Budgeting Decisions
>

### Current Assets
> Assets that could reasonably be converted into cash within one operating cycle or one year, whichever takes longer.

> Support the long-term investment decisions of a company.

> Includes:
- Cash
- Marketable securities
- Accounts receivable
- Inventories

### Compounding
> Traslating a current value into its equivalent future value.

> Earning interest on interest. The balance at any time is a combination of the [Principal](#principal), [Interest](#interest) on princiapl, and *interest on accumulated interest* ([Interest on Interest](#interest-on-interest))

### Compound Interest
>
> An investment may pay interest more than one time per year:
- Semiannually
- Quarterly
- Monthly
- Weekly
- Daily

> [See also: Interest](#interest)
> [See also: Compounding](#compounding)

### Compound Factor
> Rate of exchange between present dollars and dollars $N$ compounding periods into the future.

### Continuos Compounding
> The extreme frequency of compounding. Interest is compounded instantaneously.
> The [Factor](#compound-factor) for compounding continously for *one year* is $e^{APR}$. Where $e = 2.71828...$

$$
\begin{equation}
FV = PV e^{N(APR)}
\end{equation}
$$
> $N$: compounded years.

### Cash Flows
> 

[Go to: Table of contents](#table-of-contents)

---

## D

### Discounting
> Translating a future cash flows or value into its equivalent value in a prior period.
> Translates a FV into a PV.

### Depreciation
> A negative growth.

[Go to: Table of contents](#table-of-contents)

---

## E

### End-of-period Cash Flows ($CF$)
>

[Go to: Table of contents](#table-of-contents)

---

## F

### Finance 
> Application of the economic principles to decision-making that involves the allocation of money under conditions of uncertainty.

> Also known as: *Financial Economics*.

### Financial Analysis
> Involves the selection, evaluation, and interpretation of financial data and other pertinent information to assist in evaluating the operating performance and financial conditions of a company.

### Financial System
> Consists in three components: 
- Financial Markets
- Financial intermediaries
- Financial regulators

### Financial Management
> Also known as: *Business Finance* or *Corporate Finance*.

> The specialty area of finance concerned with financial decision-making within a business entity. 

### Financial Engineering
> Involves the restructuring or replacing of cash flows and/or the use of derivative instruments.

> Also known as: *Structure Finance*.

### Future Value
> 
$$
\begin{equation}
\text{Future value} = \text{Present value} + \text{Interest}
\end{equation}
$$

$$
\begin{equation}
\begin{aligned}
FV &= PV + (PV \cdot i) \\
&= \text{Principal} + \text{Interest}
\end{aligned}
\end{equation}
$$

> Future Value with [Simple Interest](#simple-interest):
$$
\begin{equation}
FV = PV (1 + i)
\end{equation}
$$

> Future Value with [Compound Interest](#compound-interest) ([Basic Valuation Factor](#basic-valuation-factor)):
$$
\begin{equation}
FV = PV (1 + i)^N
\end{equation}
$$
- $N$: **number of compounding periods**.
- $(1 + i)^N$: **[Compound Factor](#compound-factor)**.

### Future Value Annuity Factor
> Sum of the **compounding factors** for a given interest rate $i$, and number of periods $N$.
$$
\begin{equation}
\sum_{t = 1}^{N} (1 + i)^{N - t}
\end{equation}
$$

> An alternative formula for the sum of the compound factos for large numbers of periods is:
$$
\begin{equation}
\text{Future value annuity factor} = \frac{(1 + i)^N - 1}{i}
\end{equation}
$$

[Go to: Table of contents](#table-of-contents)

---

## G

### Growth Rate
> Rate at which a value [appreciates](#appreciation) or [depreciates](#depreciation) over time.

> We can express the change in the value of the savings balance (the difference between the ending value and the beginning value).

### Geometric Average Return
$$
\begin{equation}
i = \sqrt[N]{\frac{FV}{PV}} - 1
\end{equation}
$$
- $N$: number of compounding periods
- $FV$: Future value
- $PV$: Present value

### Guaranteed Investment Contract (GIC)
> Common investment product of a life insurance company.
> An insurance company guatantees a specified interest rate for a period of years.

[Go to: Table of contents](#table-of-contents)

---

## I

### Investment Decisions
> Concerned with the use of funds: 
- Buying
- Holding
- Selling

### Investment Management
> Specialty area within finance dealing with the management of individual or institutional funds.

> Also known as: *Asset management*, *Portfolio management*, *Money management* and *Wealth management*.

> Involves five activities:
1. Setting investment objectives: thorough analysis of what the entity wants to accomplish.
2. Establishing an investment policy: policy guidelines must be established, taking into consideration any client-imposed investment constraints, legal/regulatory constraints, and tax restrictions. This task begins with the **asset allocation decision** (i.e., how the funds are to be allocated among the major asset classes).
3. Selecting an investment strategy: a portfolio strategy that is consistent with the investment objectives and investment policy guidelines must be selected.
4. Selecting the specific assets: selecting the specific financial assets to include in the portfolio, which is referred to as the **portfolio selecting problem**.
5. Measuring and evaluating investment performance

### Interest
> Compensation for the **use of funds** for a specific period.

> It consists of:
- Compensation for the length of time the money is borrowed
- Compensation for the risk that the amount borrowed will not be repaid exactly as set forth in the **loan agreement**.

### Interest on Interest
> Interest on accumulated interest.

[Go to: Table of contents](#table-of-contents)

---

## L

### Liability
> The amount a [Life insurance company] has agreed to pay. ???

> [See also: GIC](#guaranteed-investment-contract-gic)

### Loan Amortization
> (Analysis of the repayment of a loan).
> **Repayment of a loan** with **equal payments** over a **specified period of time**.

> Each successive payment pays off a greater amount of the loan - as the principal amount of the loan is reduced, less of each payment goes to paying off interest and more goes to reducing the loan principal.

[Go to: Table of contents](#table-of-contents)

---

## M

### Multiple Rates
> Calculation of a future value considering different interest rates or growth rates for different periods.

$$
\begin{equation}
FV = PV(1 + i_1)(1 + i_2)(1 + i_3)...(1 + i_N)
\end{equation}
$$
> $i_N$: interest rate for period $N$.

> [See alse: Compounding](#compounding)
> [See alse: Compound Interest](#compound-interest)

[Go to: Table of contents](#table-of-contents)

---

## N

### Number of Compounding Periods ($N$)
> 

$$
\begin{equation}
N = \frac{\ln(FV) - \ln(PV)}{\ln(1 + i)}
\end{equation}
$$

> We **round off** to the **next whole period** because the interest is paid at the end of each month.

[Go to: Table of contents](#table-of-contents)

---

## O

### Ordinary Annuity
> Special form of [annuity](#annuities), where the first cash flow occurs at the end of the first period.

> Future value of an ordinary annuity:
$$
\begin{equation}
\begin{aligned}
FV &= \sum_{t = 1}^{N} {CF (1 + i)^{N - t}} \\
&= CF \sum_{t = 1}^{N} (1 + i)^{N - t}
\end{aligned}
\end{equation}
$$

> Present value of an ordinary annuity:
$$
\begin{equation}
\begin{aligned}
PV &= \sum_{t = 1}^{N} {CF \left( \frac{1}{(1 + i)} \right)^t} \\
&= CF \sum_{t = 1}^{N} \left( \frac{1}{(1 + i)} \right)^t \\
&= CF \sum_{t = 1}^{N} \frac{1}{(1 + i)^t}
\end{aligned}
\end{equation}
$$
> $t$: time period corresponding to a particular cash flow.

[Go to: Table of contents](#table-of-contents)

---

## P

### Principal
> 

### Theory of Portfolio Selection
> Formualted by Harry Markowitz in 1952.
> This theory proposes how investors can construct portfolios based on two parameters:
- **Mean return**
- **Standard deviation of returns** *(meassure of risk)*

### Present Value
> 

$$
\begin{equation}
\begin{aligned}
PV &= \frac{FV}{(1 + i)^N} \\
&= FV \left( \frac{1}{1 + i} \right)^N \\
&= FV \left[ \frac{1}{(1 + i)^N} \right]
\end{aligned}
\end{equation}
$$

> If the frequency of compounding is greater than once a year, we make adjustements to the **rate per period ($i$)** and the **number of periods ($N$)**.

### Present Value Annuity Factor
> Sum of the **discounting factors** for a given interest rate $i$, and number of periods $N$.
$$
\begin{equation}
\sum_{t = 1}^{N} \frac{1}{(1 + i)^{t}}
\end{equation}
$$

> Another more convenient way of solving for the PV of an annuity is to rewrite the factor as:
$$
\begin{equation}
\text{Present value annuity factor} = \frac{1 - \frac{1}{(1 + i)^N}}{i}
\end{equation}
$$

[Go to: Table of contents](#table-of-contents)

---

## R

### Risk
>

### Return
> The income on an investment, generally stated as a change in the value of the investment over each period divided by the amount at the investment at the beginning of the period.

### Risk Management
> Involves determining which risks to **accept**, which to **neutralize**, and which to **transfer**.

> Four key processes in risk manegement:
1. Risk identification
2. Risk assessment
3. Risk mitigation
4. Risk transferring

> [See also: Risk](#risk)

[Go to: Table of contents](#table-of-contents)

---

## S

### Simple interest
> Interest that repeats itself in exactly the same way from one period to the next as long as the interest is taked out at the end of each period and the princiapl remains the same.

> [See also: Interest](#interest)
> [See also: Principal](#principal)

[Go to: Table of contents](#table-of-contents)

---

## T

### Time Value of Money
>
> Cash flows occuring at different points in time have different values relative to any one point in time.
> Cash flows are uncertain.

> [See also: Compounding](#compounding)
> [See also: Discounting](#discounting)

### Time Value of a Series of Cash Flows
> Determination of the present or future value of a series of cash flows.
> If not withdrawals are made.

$$
\begin{equation}
\begin{aligned}
PV &= CF_0 \left( \frac{1}{1 + i} \right)^0 + CF_1 \left( \frac{1}{1 + i} \right)^1 + ... + CF_N \left( \frac{1}{1 + i} \right)^N \\
&= \sum_{t = 0}^{N}{CF_t \left( \frac{1}{1 + t} \right)^t}
\end{aligned}
\end{equation}
$$
> The present value of a series of cash flows is the sum of the products of each cash flow and its corresponding discount factor.

> In many real-world applications multiple interest rates are used. 
> The interest rate that can be earned depends on the amount of time the investment is expected to be **outstanding**.
> Typically, there is a **positive relationship** between **interest rates** and the **length of time the investment must be held**.
> The formula for the PV of a series of cash flows when there is a different interest rate:
$$
\begin{equation}
\begin{aligned}
PV &= CF_0 \left( \frac{1}{1 + i_0} \right)^0 + ... + CF_N \left( \frac{1}{1 + i_N} \right)^N \\
&= \sum_{t = 0}^{N}{CF_t \left( \frac{1}{1 + i_t} \right)^t}
\end{aligned}
\end{equation}
$$

> [See also: Cash Flows](#cash-flows)
> [See also: End-of-period Cash Flows](#end-of-period-cash-flows-)
> [See also: Yield Curve](#yield-curve)

[Go to: Table of contents](#table-of-contents)

---

## V

### Valuation
> Process of determing the fair value of a financial asset.

> It's fundamental principle is that the value of any financial asset is the present value of the expected cash flows.

> The valuation of a financial asset involves:
1. Estimating the expected cash flows
2. Determining the appropiate interest rate or interest rates that should be used to discount the cash flows
3. Calculating the present value of the expected cash flows using the interest rate or interests rates

[Go to: Table of contents](#table-of-contents)

---

## Y

### Yield Curve
> The relationship between **interest rates on investments** and the **length of time investment must be held**.

[Go to: Table of contents](#table-of-contents)

---

# Notas
- Los términos están ordenados alfabéticamente.
- Cada término incluye una definición concisa y, opcionalmente, una fórmula o ejemplo.