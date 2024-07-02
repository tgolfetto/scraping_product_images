# Automated Product Image Enrichment for Employee Discount Program
This project tackles a challenge within our company's employee discount program. Currently, employees receive a CSV file listing clearance stock available at a discount, but it lacks product images. This makes it difficult for them to visualize the products and take advantage of the discount program effectively.

| **ID** | **Image** | **Season** | **Brand** | **SKU**                  | **Description** | **Style**  | **Colour Code** | **Colour Desc** | **Size** | **Gender** | **Category** | **Sub-Category** | **DDP-EUR** | **Alpi Servizio Moda** | **Alpi UK** |
|------|-----------|------------|-----------|--------------------------|-----------------|------------|-----------------|-----------------|----------|------------|--------------|------------------|-------------|------------------------|-------------|
| 1    | ![COPBLKAW23](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5bhUcrCbymhI4MovVX5nOzFZ9LurEyH4VvQX-nCdiU7O_AvjK6adyIv9iRg&s) | CARRYOVER  | 13 09 SR  | COPBLKAW23-BLACK-40      | Copy            | COPBLKAW23 | BLACK           | BLACK           | 40       | WOMEN      | Shoes        | Boots            | 0           | 1                      |             |
| 2    | ![MIKBLKAW22](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_ceYV0wajhgqJuHG_1dhZ8_JlQB9t_Cee_QUr38r9V1t-qQ1tCsjKvjvJ-Q&s) | CARRYOVER  | 13 09 SR  | PAW22MIKBLKAW22-BLACK-36 | Miky            | MIKBLKAW22 | BLACK           | BLACK           | 36       | WOMEN      | Shoes        | Ballerina Shoes  | 0           | 1                      |             |


## Solution

I've developed a Google Colab Jupyter Notebook that takes the discount CSV file as input and fetches product images from Google Images. It then generates an enriched HTML file that displays the original product information alongside the fetched images. The script allows for filtering by warehouse or brand to better target employees' interests and improve the shopping experience. To optimize image retrieval and reduce unnecessary queries to Google Images, a logging system tracks previously fetched images.

## Benefits

- **Improved Product Visualization:** Employees can now easily visualize the clearance products, leading to better decision-making when utilizing the discount program.
- **Increased Employee Satisfaction:** Enhanced product visualization fosters a more positive user experience with the discount program.
- **Enhanced Program Engagement:** Clearer product representation through images results in increased program engagement from employees.

## Disclaimer
Data and solution details are anonymized for privacy reasons. This project focuses on publicly available information regarding past-season stock.
