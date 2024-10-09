# BLADE Bench

This website is adapted from [Nerfies website](https://nerfies.github.io).

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


## Update the leaderboard

```sh
cd mathvista.github.io
cd data/results

python3 process_outputs.py
python3 process_scores.py

git add -A
git commit -m "Update leaderboard"
git push
```
