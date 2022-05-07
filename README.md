# verify_relationship_game

## Description
Given a weight vector, to check whether a relationship game (RG) satisfies some LTL properties.

## Getting Started
### Installing
PRISM and PRISM-GAMES: see instruction https://www.prismmodelchecker.org

### Running

#### PRISM: partial verification
* TS model induced by given pure strategy in 
```
prism_files/traffic2_partial_pure.prism
```
* MDP model induced by given mixed strategy in 
```
prism_files/traffic2_partial_mixed.prism
```
* Partial verification property list
```
prism_files/traffic2_partial.props
```

#### PRISM-GAMES: full verification
* Game model in
```
prism_games_files/traffic2_game.prism
```
* Full verification property list
```
prism_games_files/traffic2_game.props
```

### Acknowledgments
The Game model is adapted from the prisoner's dilemma example on prism-games website: https://www.prismmodelchecker.org/games/examples/prisoners_dilemma.prism
