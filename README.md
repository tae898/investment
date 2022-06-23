# investment

lump sum vs. dollar cost averaging.

I wasn't sure if ["Lump-sum investing outperforms dollar cost averaging almost 75% of the time"](https://www.experian.com/blogs/ask-experian/dollar-cost-averaging-vs-lump-sum-investing/#:~:text=Lump%2Dsum%20investing%20outperforms%20dollar%20cost%20averaging%20almost%2075%25%20of,sum%20could%20yield%20better%20results.) is actually true. So I ran a small script.

Check out [`investment.ipynb`](./investment.ipynb)

## Some insights

```console
Chance of winning by investing every 2 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 4 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.9131
Chance of winning by investing every 8 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.5417
Chance of winning by investing every 16 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.4437
Chance of winning by investing every 32 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.3476
Chance of winning by investing every 64 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.1169
Chance of winning by investing every 128 trading days, for 1 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
division by zero
division by zero

Chance of winning by investing every 2 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 4 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 8 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.7587
Chance of winning by investing every 16 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.4558
Chance of winning by investing every 32 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.3361
Chance of winning by investing every 64 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.1123
Chance of winning by investing every 128 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0025
Chance of winning by investing every 256 trading days, for 2 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
division by zero

Chance of winning by investing every 2 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 4 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 8 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.9366
Chance of winning by investing every 16 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.4923
Chance of winning by investing every 32 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.336
Chance of winning by investing every 64 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.1266
Chance of winning by investing every 128 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 256 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 512 trading days, for 4 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0

Chance of winning by investing every 2 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 4 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 8 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 16 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.8553
Chance of winning by investing every 32 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.3775
Chance of winning by investing every 64 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.1998
Chance of winning by investing every 128 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 256 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 512 trading days, for 8 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0

Chance of winning by investing every 2 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 4 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 8 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 16 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 32 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.4925
Chance of winning by investing every 64 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.1715
Chance of winning by investing every 128 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 256 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 512 trading days, for 16 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0

Chance of winning by investing every 2 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 4 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 8 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 16 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 32 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 1.0
Chance of winning by investing every 64 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.1089
Chance of winning by investing every 128 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 256 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
Chance of winning by investing every 512 trading days, for 32 year(s) when inflation is fixed at 0.04, compared to investing at once: 0.0
```

## Prerequisites

1. A unix or unix-like x86 machine
1. python 3.8 or higher.
1. Running in a virtual environment (e.g., conda, virtualenv, etc.) is highly recommended so that you don't mess up with the system python.
1. `pip install -r requirements.txt`

## TODOs

1. Double check the math
1. Try other ticker symbols.
1. Try cryptos.
1. Come up with a better inflation rate, based on the investment starting date.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
1. Run `make style && make quality` in the root repo directory, to ensure code quality.
1. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
1. Push to the Branch (`git push origin feature/AmazingFeature`)
1. Open a Pull Request

## Authors

- [Taewoon Kim](https://taewoon.kim/)
