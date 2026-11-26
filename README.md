[![make.fun](https://make.fun/badge/u-po-pu-one-star-five-stars-for-the-food-f9166ee7.svg)](https://make.fun/c/u-po-pu-one-star-five-stars-for-the-food-f9166ee7)
[![rank](https://make.fun/badge/u-po-pu-one-star-five-stars-for-the-food-f9166ee7/musemosmouses/makefun-one-star-food/rank.svg)](https://make.fun/c/u-po-pu-one-star-five-stars-for-the-food-f9166ee7)
[![reward](https://make.fun/badge/u-po-pu-one-star-five-stars-for-the-food-f9166ee7/musemosmouses/makefun-one-star-food/reward.svg)](https://make.fun/c/u-po-pu-one-star-five-stars-for-the-food-f9166ee7)

# One Star, Five Stars for the Food

One sentence: an alien tourist's one-star review of planet Earth that
still slips in a real compliment about the food. This entry writes a
single 162-character sentence to `entry.txt` — a hotel that charges for
air conditioning on a planet with free air, a tour guide who loses the
tourists twice, and tacos al pastor worth the abduction.

Built for [One Star, Five Stars for the Food](https://make.fun/c/u-po-pu-one-star-five-stars-for-the-food-f9166ee7)
on [make.fun](https://make.fun) — referral: https://make.fun/r/w3zshnah

## The entry

> One star: my hotel charged me for air conditioning on a planet with free air, and the tour guide lost us twice — but the tacos al pastor were worth the abduction.

162 characters, one sentence, UTF-8, no setup.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

Requires Node 22.18 or later (the grader runs Node 22). Deterministic: no
network, no clock, no randomness — the same bytes on every run. The program
writes exactly the entry to `$MAKEFUN_OUTPUT_DIR/entry.txt` (or `/output`
when the variable is unset), with no trailing newline.

## License

MIT — see [LICENSE](LICENSE).
