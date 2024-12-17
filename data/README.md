# Data folder

## Folders

source data:
- https://collegefootballdata.com/exporter

- https://knightnewhousedata.org/fbs

### raw
Original, unmodified data after downloading, scraping, etc

### final
Data after all cleaning, processing, and analyzing.

---

## Data Dictionary

The following table provides details about the columns included in the dataset:

| **Column**            | **Type**   | **Source**             | **Description**                                              |
|------------------------|------------|------------------------|--------------------------------------------------------------|
| `team`                | Text       | both                   | Name of the college football team                           |
| `year`                | Numeric    | both                   | Year of the football season                                 |
| `wins`                | Numeric    | CFB Data API           | Total number of games won in the season                     |
| `losses`              | Numeric    | CFB Data API           | Total number of games lost in the season                    |
| `conference`          | Text       | CFB Data API           | Conference to which the team belongs                        |
| `average_attendance`  | Numeric    | CFB Data API           | Average attendance at home games                            |
| `bowl_game`           | Text       | CFB Data API           | Name of the bowl game if the team played in one             |
| `total_revenue`       | Numeric    | Knight-Newhouse        | Football program revenue for the season                     |
| `total_expenses`      | Numeric    | Knight-Newhouse        | Football program expenses for the season                    |

---