A neural network that classifies wine as red or white from 12 chemical measurements (acidity, sugar, sulfur dioxide, etc.).Thenafter it,checks why it works using SHAP, and compares that against real oenology research.

## Results:

Accuracy: ~99% neural networks and a simple logistic regression baseline hit this the classes are nearly linearly separable

Top features the model relies on (via SHAP): total sulfur dioxide, density, residual sugar, chlorides, alcohol

Conclusions I observed through the figure:

1)Total sulfur dioxide : Low on red wine and High on white wine

2)Density : High on red wine and low on white wine

3)Residual sugar : High on white wine 

4)Chlorides : High on red wine

5)Volatile acidity : High on red wine



## Data Source

archive.ics.uci.edu/dataset/186/wine+quality

## References

Effect of free SO₂ on red/white wine acidity

Oenological tannins as SO₂ alternatives

Skin contact and phenolics in white winemaking

SO₂-flavanol sulfonation differs by wine style
