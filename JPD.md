
# Joint Probability Distribution Formulas

| Expression | Discrete | Continuous |
|-----------|----------|------------|
| p(x,y) | P(x=x, y=y) | f(x,y) |
| f(x) | ∑ᵧ p(x,y) | ∫ f(x,y) dy |
| f(y) | ∑ₓ p(x,y) | ∫ f(x,y) dx |
| E(x) | ∑ₓ x f(x) | ∫ x f(x) dx |
| E(y) | ∑ᵧ y f(y) | ∫ y f(y) dy |
| E(xy) | ∑ₓ ∑ᵧ x y p(x,y) | ∫∫ x y f(x,y) dx dy |
| V(x) | E(x²) − [E(x)]² | E(x²) − [E(x)]² |
| V(y) | E(y²) − [E(y)]² | E(y²) − [E(y)]² |
| COV(x,y) | E(xy) − E(x)E(y) | E(xy) − E(x)E(y) |
|ρ(x,y)|COV(x,y)/[σ(x)σ(y)]|COV(x,y)/[σ(x)σ(y)]|
