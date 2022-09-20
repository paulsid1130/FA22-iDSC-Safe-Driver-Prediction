## Phase 5 Feature Engineering & Feature Selection

![Enter image description](../../pic/feat_eng.png)

Original project link: https://www.kaggle.com/c/porto-seguro-safe-driver-prediction

### ❤️ Stage goals

#### Master the applicable scenarios and implementation methods of feature engineering

##### 5 major coding methods

- label encoding
- ordinal encoding
- onehot encoding
- target encoding 🔥🔥
- clustering encoding 🔥🔥

![Enter image description](../../pic/feat_enc.png)

##### Data binning

- Unsupervised: equidistant, equal frequency
- Supervised: Chi-square, minimum entropy 🆕
- WOE/IV contribution 🆕

##### Data conversion

- scaling
- normalization
- clipping
- log scaling
- z-score


![Enter image description](../../pic/scale.png)


##### Feature Enhancement
- Feature interactions:
    - Polynomial construction
- Feature transformation
    - GBDT+LR
    ![Enter image description](../../pic/GBDT_LR.png)
- Feature dimensionality reduction
    - pca
    - T-SNE



##### Feature selection

![Enter image description](../../pic/feat_select.png)

- Based on statistical indicators
    - Variance
    - Correlation
    - Gini Coefficient
    - Information gain
- Model based
    - tree model
    - RFE etc.