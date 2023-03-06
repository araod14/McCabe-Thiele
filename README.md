#McCabe-Thiele

This jupyter notebook describes the calculation of the number of plates necessary for the separation of two compounds according to the **McCabe-Thiele method**

## Information input for equilibrium curve
- alphaa=6.88 **relative volatility**

Alpha could be calculated by the ratio of the  K  values for the two components::

![{\displaystyle \alpha ={\frac {K_{i}}{K_{j}}}={\frac {(y_{i}/x_{i})}{(y_{j}/x_{j})}}}](https://wikimedia.org/api/rest_v1/media/math/render/svg/7b199a28763c6492c2c9d071bf148faf21689bd9)
## Output
![image](https://user-images.githubusercontent.com/99058835/223166379-d90e9510-a65a-4cec-89be-398c06084322.png)

## Information input for plates calculate
- f=100   **Flow - kmol/h**
- xd=0.95 **Distillate composition**
- xb=0.03 **Bottoms composition**
- z=0.45  **Feed composition**
- q=0.5   **Vapor feed**

## Output
![image](https://user-images.githubusercontent.com/99058835/223165423-6dc9c884-9334-4ed3-beb2-6f7e6ca9fcc9.png)
```
print(f"El numero de platos de la torre de destilacion requeridos para la separacion es: {i}")
El numero de platos de la torre de destilacion requeridos para la separacion es: 7
```
