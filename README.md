Defeater
=======
Defeater is a wordlist used for brute-forcing passwords.

It was created by merging many different leaked-password wordlists
(including rockyou), and then expanding (i.e. mutating) the wordlist
with similar variations of the already-existing passwords, using
[PassMutate](https://github.com/kaimosensei/passmutate).

Though it has a significantly higher hit rate than rockyou, it is much
larger and not sorted by individual word frequency, so it is recommended
that this is used in the case that rockyou failed first.

## Download
At the moment it can only be downloadable via torrent.

You can either download the torrent file in the release or use this
magnet link:

```
magnet:?xt=urn:btih:627e0e1da7882e979b2915054128f195da4223dc&dn=defeater.txt.gz&tr=udp%3a%2f%2f9.rarbg.com%3a2810%2fannounce&tr=udp%3a%2f%2ftracker.openbittorrent.com%3a6969%2fannounce
```

Please help spread Defeater by helping seed.

## Statistics
- **Lines**: 1,290,373,133
- **Compressed size**: 2.9GB
- **Uncompressed size**: 13.0GB
- **Passwords added via mutation**: 1,264,554,652 (98%)
- **Line terminators used**: Unix, \n

To determine how good Defeater is, the below wordlists were used to crack 3 hash lists and their success
rates were recorded.
- **sampled_10million**: 10,000,000 password hashes of varying commonness.
- **first_million**: The 1,000,000 most common passwords.
- **last_million**: The 1,000,000 least common passwords.

|                      | sampled_10million | first_million      | last_million     |
|----------------------|-------------------|--------------------|------------------|
| **rockyou**          | 0.67% *(67,000)*  | 68.35% *(683,500)* | 0% *(0)*         |
| **defeater**         | 5.57% *(557,000)* | 92.81% *(928,100)* | 2.43% *(24,300)* |

*See the [PassMutate](https://github.com/kaimosensei/passmutate) for a
more detailed comparison between rockyou and defeater.

## Contact
If you're having trouble downloading the file or have any questions,
please email me at kaimo.sec@protonmail.com