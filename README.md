# Predict-Portfolio-Returns-by-Autoencoder-Model-
I constructed below autoencoder models. There are two inputs. The left side is beta exposure, the righ side is factor returns. After walking through multiple layers, I dotted the outputs of the two sides. I trained the model to let the dotted outputs equal to real portfolio returns. 
![autoencoder](https://github.com/EmmaZhangXuan/IMG/blob/master/WeChat%20Screenshot_20190913111846.png)
When I tuned the model, I changed the number of denses in beta side and also the number of dotted outputs' nodes, which means that the number of factors to predict returns.
Below this the final outcome. 
![autoencoder](https://github.com/EmmaZhangXuan/IMG/blob/master/WeChat%20Screenshot_20190913112509.png)
We can see that autoencoder models have a much higher r_squared than linear regression.
