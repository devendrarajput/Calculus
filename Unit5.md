# Unit 5 - Analytical Application of Differentiation

## MVT - Mean Value Theorem
- 2nd existence theorem
    - Condition 1: f(x) should be continuous in closed interval [a, b] i.e. pictorially no holes, jumps etc.
    - Condition 2: f(x) should be differentiable in open interval (a, b) i.e. pictorially no cusps
    - There exists a point "c" between "a" and "b", where instantaneous rate of change = Average rate of change i.e. pictorially Slope of (a, f(a)) and (b, f(b)) = Slope of f'(x)
    - Average rate of change = f(b) - f(a) / b - a
    - 🎦 MVT.PNG

> [Q1] Use the function f (x) = —x² + 3x + 10 to answer the following.
> 1. On the interval [2, 6], what is the average rate of change?
> 2. On the interval (2, 6), when does the instantaneous rate of change equal the average rate of change?
> 🎦 Q1.PNG

## IVT - Intermediate Value Theorem
- 1st existence theorem
    - Condition 1: f(x) should be continuous in closed interval [a, b] i.e. pictorially no holes, jumps etc.
    - For a given interval [a, b] the y values at endpoints will be f(a) and f(b)
    - IVT guaranteed that any value of y that lies between f(a) and f(b) will always exist at least once on the function within the interval [a, b]

> [Q2]
> 🎦 Q2.PNG
> a) Yes, since the function is twice differentiable, it must be continuous. So, the IVT applies: since h(5)=40 and h(15)=70, there must be a time c within interval [5, 15] such that h(c)=50
> b) IVT doesn't apply as v(20)=2 and v(30)=4 and 1.5 doesn't lie within this interval
> Avg rate of change = h(30)-h(20)/(30-20) = (80-65)/10 = 15/10 = 1.5
> Since the function h(t) is differentiable, it must be continuous. The MVT applies and there must be some value c in interval [20,30] such that f'(c) = 1.5

## EVT - Extreme Value Theorem
   - Condition 1: f(x) should be continuous in closed interval [a, b] i.e. pictorially no holes, jumps etc.
   - EVT guarantees that f has at least one minimum value and at least on maximum value on [a, b]

## Extrema
- Global aka Absolute: Overall largest or smallest
- Local aka Relative: Largest or smallest in a "local area"

> [Q3]
> 🎦 Q3.PNG
> 🎦 A3.PNG

> [Q4]
> Find all extreme values. Identify the type and where they occur.
> 🎦 Q4.PNG
> Absolute minima of 1 at x=-3
> Absolute maxima of 5 at x=0
> Relative minima of 2 at x=1

> [Q5]
> Find all extreme values. Identify the type and where they occur.
> 🎦 Q5.PNG
> Absolute maxima of 3 at x=-1
> Relative maxima of 1 at x=1
> Maybe a relative minima of -1 at x=4

## Critical Point
- A point that has a possibility of being an extrema
- 🎦 CP.PNG
- How to find Critical Point
    - f'(x) is 0
    - f'(x) is undefined
- Critical point must be in the domain of function, so the function should have a valid value at that point

> [Q5]
> Find all critical points
> f(x)= 1/3 x³ - 9x + 24
> 🎦 Q5.PNG

> [Q6]
> Find all critical points
> g(x) = 1 / sqrt(4-x²)
> 🎦 Q6.PNG

## Increasing or Decreasing intervals
- 🎦 G7.PNG
- By looking at the graph we can say critical points are located at 
    - x = 3 as f'(x)=0
    - x = 5 as f'(x)=0
    - x = 6 as f'(x)=DNE because we have a cusp

    so let's create a sign chart 
    - 🎦 SC.PNG
> [Q7]
> Find the intervals on which the function f(x)= -x² -4x -1 is increasing and decreasing
> 1. First find the critical points
> 2. In between x-values, the derivative must be positive or negative
> 3. Draw sign chart
> 🎦 Q7.PNG
> Required justification: 
>   f(x) is increasing on (-∞, -2) since f'(x) > 0
>   f(x) is decreasing on (-2, ∞) since f'(x) < 0

> [Q8]
> Find the intervals on which the function f(x) = 1/3 x³ - x² - 15x + 2 is increasing and decreasing and justify your answers.
> 🎦 Q8.PNG

## First Derivative Test
- Purpose: To find maxima or minima for a function
    - Step 1: Take first derivative
    - Step 2: Find critical points at f'(x) = 0 or DNE
    - Step 3: Draw sign chart
    - Step 4: Identify Maxima or minima using following patterns
        -ve -> 0 -> +ve : Maxima
        +ve -> 0 -> -ve : Minima

> [9]
> f(x)= (x²-4)²/³
> Q10.PNG


> [10]
> f(x)=x²/(4-x)
> Q11.PNG

## Candidate Test
- Used for finding absolute maxima and minima
- Absolute Maxima/Minima can occur on following points
    - Critical Points
    - End points

- Candidate test Algorithm
    - Step 1: Find critical points (When first derivative is 0 or DNE)
    - Step 2: Identify candidates: Candidate will be end points of the given interval and all Critical points within the interval
    - Step 3: Find the value of function at the candidate points
    - Step 4: Absolute maxima will the point where we get maximum value at Step 3.
    - Step 5: Absolute minima will the point where we get minimum value at Step 3.

- For the given graph identify extremas
- 🎦 6.12.PNG

> [12]
> Find the absolute maximum value and absolute minimum value of the function f(x)=x³-3x²+1 on interval [-1/2, 4]
> 🎦 Q12.PNG

> [Q13]
> Looking at the graph of f'(x), identify extremas
> 🎦 Q13.PNG
> As critical points are located where f'(x) is 0, so x=1 and x=3 will be Critical Points
> At x=1, as f'(x) is going from +ve to -ve, it will be a local maxima
> At x=3, as f'(x) is going from -ve to +ve, it will be a local minima
> For finding absolute Maxima and Minima we also have to consider endpoints i.e. x=-3 and x=4
> As f'(x) is +ve from x=-3 till x=1 and then goes to -ve for sometime, we should have absolute maxima at x=1
> similarly we have a absolute minima at x=3 

## 5.6 Concavity
- Concave Up
- Concave down
- Inflection point: point where concavity changes
- Big idea 🎦 13.PNG

- 2nd derivative test algorithm
    - Step1: find first derivative only
    - Step2: find second derivative
    - Step3: Set f"(x) to 0 and find inflection points
    - Step4: Draw sign chart using inflection points
    - Step5: Mark interval as concave-up when f"(x) is +ve
    - Step6: Mark interval as concave-down when f"(x) is -ve

> [Q14]
> f(x)= 1/4x⁴-6x²+x-3
> 🎦 Q14.PNG
