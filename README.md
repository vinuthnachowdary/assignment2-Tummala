# assignment2-Tummala
# i am interested in fashion technology.
# Tummala Satya Sai Vinuthna
###### Paris

I love the fashion sense in paris. That's what I like about the city.
Paris is the city which has huge number of hotels and restaurents **City of Fashion** and the **city of Romance** in the world.

---

# Direction from Maryville to los angeles.
1. First book a cab from maryville to nearest airport.
   1. After reaching the airport check in your respective flight.
   2. Collect the boarding pass and reach your destination in the flight.

# Items to carry for the trip
* clothes
  * jeans
  * shirts
* SkinCare
  * Bodycream
  * Handcream
  * Moisturizer
  * Handcream
  * Bodybutter
* food
* camera
* shoes

[image](https://github.com/vinuthnachowdary/assignment2-Tummala/blob/main/AboutMe.md)

---

# Table Creation

The above table recommends some of my best food and drinks I experienced til now.

|           Food/Drink      |      Location            | Price |
|           ----            |      -----               | ----: |
|    Fudgy chocolate sphere |       Starbucks          | $12   |
|    Caramel Mocha Cupcake  |       Taco               | $15   |
|    Choco Ganache          |       MC D               | $14   |
|     Vanilla Milkshake     |       Joy Wok            | $11   |


---

# Quotes by Great People

> "We're here to put a dent in the universe Otherwise why else even be here?" - by ***Steve Jobs*** <br>
> "Why is it that people who can't take advice always insist on giving it?" - by ***James Bond***


---

# Algorithms on Algebra

> Algebra is one of the definitive and oldest branches of mathematics, and design of computer algorithms is one of the youngest. Despite this generation gap, the two disciplines beautifully interweave. Firstly, modern computers would be somewhat useless if they were not able to carry out arithmetic and algebraic computations efficiently, so we need to think on dedicated, sometimes rather sophisticated algorithms for these operations.

Source link for the definition - <https://www.coursera.org/learn/algebra-and-algorithms>

```
long long binpow(long long a, long long b) {
    long long res = 1;
    while (b > 0) {
        if (b & 1)
            res = res * a;
        a = a * a;
        b >>= 1;
    }
    return res;
}

```
Source link for code - <https://cp-algorithms.com/algebra/binary-exp.html>