# Abhilash Reddy Malipatlola

## Miami

Beaches of Miami are world famous and tourists and travelers come here from the whole world. **At night time Miami Beach turn into a totally different place. Miami is also famous for its night life.** Festivals are also held continuously to attract the tourists. When you will visit Miami Beach you will feel that you are in a tropical world. **This is the main reason for my interest in this location.**

****
## Diections to travel from Maryville to Chicago

1. The driving distance between Maryville to Chicago is 557 miles. It takes approximately 9h 17m to drive from Maryville to Chicago.
2. Below are the cities which come in between the travel route.
    1. Des Moines
    2. Iowa city
    3. Naperville
3. After crossing Naperville, we will reach Chicago.


Below are theitems which should be braught to the place.
* Clothes to be carried for each day. 
* For better transactions, cash should be taken.
* Below tickets to be taken before journey so that travel could be easy.
    * Tickets for skydeck.
    * Tickets for 360 chicago view.
    * Tickets for boat tour.

Let's go to and meet the [king[(https://github.com/hvrabhi/assignment2-malipatlola/blob/main/AboutMe.md)


---

## Food table

Below is a table where we can find food/drinks and its respective prices. Few items are must try.

| Food | Location | Price|
| --- | --- | --- |
| Biryani | Kansas | $90 |
| Burger | McDonald's | $10 |
| Eggs | Walmart | $14 |
| Fries | Mooyah | $7 |

---

## Life Quotes

> Life is what happens when you’re busy making other plans. Author: *John Lennon.*

> Many of life’s failures are people who did not realize how close they were to success when they gave up. Author: *Thomas A. Edison*

---

## Code Fencing: Floyd-Warshall Algorithm

The Floyd–Warshall algorithm is an example of dynamic programming, and was published in its currently recognized form by Robert Floyd in 1962. However, it is essentially the same as algorithms previously published by Bernard Roy in 1959 and also by Stephen Warshall in 1962 for finding the transitive closure of a graph, and is closely related to Kleene's algorithm (published in 1956) for converting a deterministic finite automaton into a regular expression. The modern formulation of the algorithm as three nested for-loops was first described by Peter Ingerman, also in 1962.

[Wikipedia](https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm)

~~~

for (int k = 0; k < n; ++k) {
    for (int i = 0; i < n; ++i) {
        for (int j = 0; j < n; ++j) {
            if (d[i][k] < INF && d[k][j] < INF)
                d[i][j] = min(d[i][j], d[i][k] + d[k][j]); 
        }
    }
}

~~~

[SourceCode](https://cp-algorithms.com/graph/all-pair-shortest-path-floyd-warshall.html)