# Hotel Booking Cancellation Analysis

An Excel-based analysis of hotel booking cancellations using the Hotel Booking Demand dataset. The project explores which booking, customer, and reservation attributes are associated with cancellations and compares cancellation behavior across hotel types.

## Project contents

| File | Description |
| --- | --- |
| [`Data Analysis Using Excel.xlsx`](./Data%20Analysis%20Using%20Excel.xlsx) | Excel workbook containing the analysis, calculations, and visualizations. |
| [`hotel_booking.csv`](./hotel_booking.csv) | Source dataset used for the analysis. |

## Objectives

- Measure the overall booking cancellation rate.
- Compare cancellation patterns for city hotels and resort hotels.
- Examine the effect of lead time, deposit type, customer type, market segment, and distribution channel.
- Investigate how stay details, previous booking history, and special requests relate to cancellations.
- Turn the results into practical insights for hotel reservation and revenue-management decisions.

## Dataset overview

The dataset contains reservation-level information such as:

- Hotel type and arrival date
- Length of stay and booking lead time
- Number of adults, children, and babies
- Meal plan, market segment, and distribution channel
- Deposit type and customer type
- Reserved and assigned room types
- Previous cancellations and booking history
- Average daily rate, parking spaces, and special requests
- Cancellation indicator and reservation status

The main outcome field is `is_canceled`:

- `1` — the reservation was canceled
- `0` — the reservation was not canceled

## How to use this project

1. Clone or download the repository.
2. Open `Data Analysis Using Excel.xlsx` in Microsoft Excel or a compatible spreadsheet application.
3. Review the source data and workbook calculations.
4. Use the workbook charts and summaries to explore cancellation patterns.
5. If you replace the dataset, keep the expected column names and update the workbook ranges or pivot tables as needed.

## Suggested analysis workflow

1. Check data quality and missing values.
2. Calculate the overall cancellation rate.
3. Segment results by hotel type, arrival period, deposit type, market segment, and customer type.
4. Compare cancellation rates across lead-time and stay-length groups.
5. Identify high-risk booking segments and summarize actionable findings.

## Important privacy and licensing notice

The source CSV currently includes fields that can directly identify individuals, including `name`, `email`, `phone-number`, and `credit_card`. Do not publish, share, or redistribute this file in its current form. Create an anonymized copy by removing direct identifiers and confirm that the dataset license permits the intended use before sharing it.

Do not add customer data, credentials, or other sensitive information to this repository. Any conclusions should be treated as exploratory analysis rather than proof of causation.

## License

This repository does not currently specify a separate software license. Dataset usage remains subject to the license and terms of the original data source.
