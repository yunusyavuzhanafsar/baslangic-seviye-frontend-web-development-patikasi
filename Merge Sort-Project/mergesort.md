# Merge Sort Project 2

## [16,21,11,8,12,22] --> Merge Sort

### 1st Question-) Write the stages of the above sequence according to the sort type.

```

                   [16,21,11,8,12,22]
                            ⬇
              ------------------------------
             |                              |
        [16,21,11]                      [8,12,22]
             ⬇                              ⬇
      ----------------               ----------------
      |              |               |              |
    [16]         [21,11]            [8]         [12,22]
     ⬇             ⬇  ⬇              ⬇            ⬇  ⬇
    [16]         [21] [11]          [8]         [12] [22]
     ⬇             ⬇   ⬇             ⬇            ⬇  ⬇
    [16]         [11,21]            [8]         [12,22]
       ↘           ↙                  ↘           ↙

             ⬇                              ⬇

        [11,16,21]                      [8,12,22]

              ↘                           ↙
                ------------------------
                   [8,11,12,16,21,22]



```

### 2nd Question-) Write the Big-O notation.

```
Merge Sort of Big-O notation is O(nlogn).

Average case Complexity: O(n*log n)

Worst case Complexity: O(n*log n)

Best case Complexity: O(n*log n)

```
