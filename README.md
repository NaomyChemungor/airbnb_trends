# Airbnb Data Trends

## Metadata

### `airbnb_price.csv`
- Contains listing prices and locations.
- Columns: `listing_id`, `price`, `nbhood_full`.

### `airbnb_room_type.xlsx`
- Contains listing descriptions and room types.
- Columns: `listing_id`, `description`, `room_type`.

### `airbnb_last_review.tsv`
- Contains host names and review dates.
- Columns: `listing_id`, `host_name`, `last_review`.

## Script Details

This script analyzes Airbnb data from the above files, performs data processing, and extracts insights such as earliest and most recent reviews, number of private rooms, and average listing price.

## Usage

1. **Install Dependencies:** Run `pip install pandas numpy`.
2. **Run the Script:** Execute `airbnb.ipynb`.
3. **View Output:** Check the printed `review_dates` DataFrame.

## Files

- `airbnb.ipynb`: Airbnb data analysis script.
- `data/airbnb_price.csv`: Listing prices and locations.
- `data/airbnb_room_type.xlsx`: Listing descriptions and room types.
- `data/airbnb_last_review.tsv`: Host names and review dates.
