# Contents
* [Dataset overview](#dataset-overview)
* [Dataset analysis](#dataset-analysis)
* [Used libraries and packages](#used-libraries-and-packages)

# Dataset overview
## Metadata after cleansing
|     Column      | Non-Null Count |        Dtype       |
| ----------------|----------------|--------------------|
| event_time      |      433938    | datetime64[ns, UTC]|
| order_id        |      433938    |       int64        | 
| product_id      |      433938    |       int64        |
| category_id     |      433938    |       float64      |
| brand           |      419890    |       object       |
| price           |      433938    |       float64      |
| user_id         |      433938    |       float64      |
| product_category|      433938    |       object       |

dtypes: datetime64[ns, UTC](1), float64(3), int64(2), object(2)
memory usage: 26.5+ MB

## Reference
https://www.kaggle.com/mkechinov/ecommerce-purchase-history-from-electronics-store

# Dataset analysis
In order to provide valuable analysis I prepared:
* List of orders with the details.
* Sales data from the store over the time.
* List of product categories available in shop with selling history details.
* List of brands available in shop with selling history details.
* List of the selling details in particular months.

Implementation of the recommendation system is based on the currently added products.

# Used libraries and packages
* numpy 
* pandas 
* matplotlib 
* seaborn 
* mlxtend
* pyplot
