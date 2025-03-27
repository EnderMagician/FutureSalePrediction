# Dataset Description
You are provided with daily historical sales data. The task is to forecast the total amount of products sold in every shop for the test set. Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.

## File Descriptions

| File Name               | Description                                                                                     |
|-------------------------|-------------------------------------------------------------------------------------------------|
| sales_train.csv         | The training set. Contains daily historical sales data from January 2013 to October 2015.       |
| test.csv                | The test set. Requires forecasting sales for shops and products for November 2015.              |
| sample_submission.csv   | A sample submission file showing the correct format for predictions.                            |
| items.csv               | Supplemental information about the items/products.                                              |
| item_categories.csv     | Supplemental information about the item categories.                                             |
| shops.csv               | Supplemental information about the shops.                                                       |

## Data Fields

| Field Name            | Description                                                                                     |
|-----------------------|-------------------------------------------------------------------------------------------------|
| ID                    | An ID that represents a (Shop, Item) tuple within the test set.                                |
| shop_id               | Unique identifier of a shop.                                                                   |
| item_id               | Unique identifier of a product.                                                                |
| item_category_id      | Unique identifier of item category.                                                            |
| item_cnt_day          | Number of products sold (daily). You'll predict the monthly amount of this measure.            |
| item_price            | Current price of an item.                                                                      |
| date                  | Date in format dd/mm/yyyy.                                                                     |
| date_block_num        | Consecutive month number (January 2013 = 0, February 2013 = 1, ..., October 2015 = 33).       |
| item_name             | Name of the item.                                                                              |
| shop_name             | Name of the shop.                                                                              |
| item_category_name    | Name of the item category.                                                                     |

## Additional Information
This dataset is permitted to be used for any purpose, including commercial use.