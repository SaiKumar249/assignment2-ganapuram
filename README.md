# Sai Kumar Ganapuram

## Mancherial

Mancherial is my favorite location. It is my home town and the reason for it being my favorite place is, it is **modern** enough town with a beautiful **country side** as well which makes it a very special place for me.

---

### To reach Mancherial

1. Book a flight ticket from Kansas city airport to Hyderabad airport.
2. Board a bus to Mancherial in the airport or you can board a trains as well if you want to experiance a train journey.
    1. Get to the Secundrabad railway station to board a train to Mancherial.

### Suggested item to bring along

* Camera
* Sunscreen lotion
* Camping tent

**[Aboutme](AboutMe.md)**

---

### Food recommend

Food/drinks I would suggest 

| Food | Available Location | Cost to Prepare |
| --- | --- | --- |
| Dum Biriyani | Hyderabad, India | 3 - 5$ |
| Shawarma | Hyderabad, India | 1 - 2$ |
| Lassi or Falooda | Hyderabad, India | 1 - 2$ |
| Apricot Delight | Hyderabad, India | 1 - 2$ |

---

### QUOTES

>Arise, awake, and stop not till the goal is reached - *Swami Vivekananda*
>
>Tomorrow never comes, it is always today. - *Osho*

---

### Floyd-Warshall Algorithm

>In computer science, the Floyd–Warshall algorithm is an algorithm for finding shortest paths in a directed weighted graph with positive or negative edge weights. A single execution of the algorithm will find the lengths (summed weights) of shortest paths between all pairs of vertices.

**[Source](https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm)**

```

for (int k = 0; k < n; ++k) {
    for (int i = 0; i < n; ++i) {
        for (int j = 0; j < n; ++j) {
            d[i][j] = min(d[i][j], d[i][k] + d[k][j]); 
        }
    }
}

```

**[Source](https://cp-algorithms.com/graph/all-pair-shortest-path-floyd-warshall.html)**