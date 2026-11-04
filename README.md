# QuintOpenings
A program for the creation of an opening database from games. It reads a PGN file (e.g. a monthly Lichess database), filters games by rating and time control, and keeps moves that are played often enough in each position up to a given depth. QuintBot's opening book was built with it.

## Run
```sh
pip install chess
python src/openings.py
```
Set the path to the PGN file and the thresholds (rating, frequency, number of games, depth) at the bottom of `src/openings.py` first.
