# Hotel Booking Demand Storytelling

Data storytelling project focused on uncovering demand differences between an **urban hotel** and a **resort hotel** through visual analytics and narrative visualization.

## Interactive Visualization

**Live story:** [View the interactive Flourish story](https://public.flourish.studio/story/3660287/)

## Project Overview

This repository presents a visual storytelling analysis built from the **Hotel Booking Demand** dataset.  
The project explores whether both hotel types follow a similar demand pattern or whether they reflect **different booking behaviors**.

The final narrative is structured around four analytical dimensions:

- **Temporal dynamics** of reservations
- **ADR distribution** (Average Daily Rate)
- **Cancellation behavior**
- **Approximate stay profile**

The central conclusion is that the dataset should not be interpreted as a single homogeneous demand process.  
Instead, the urban hotel and the resort show **distinct patterns** in pricing, booking stability, and stay composition.

## Main Insights

- The **urban hotel** concentrates a higher booking volume in absolute terms.
- Its **ADR distribution** is shifted toward higher values.
- It also shows a **higher cancellation rate**, suggesting a more flexible or less stable demand pattern.
- The **resort** displays a demand structure relatively more associated with **mixed and leisure-oriented stays**.

## Repository Structure

```text
hotel-booking-demand-storytelling/
│
├── README.md
├── hotel_bookings.Rmd
└── hotel_bookings.csv
````

## File Description

### `hotel_bookings.Rmd`

R Markdown file containing the exploratory visual analysis and the analytical process used to identify the main patterns later transformed into the final story.

### `hotel_bookings.csv`

Dataset used in the analysis.

### `README.md`

Project documentation and direct access to the published interactive visualization.

## Analytical Approach

The project follows a simple but effective visual analytics workflow:

1. **Exploratory inspection of the dataset**
2. **Detection of inconsistent or problematic records**
3. **Comparison of distributions and proportions**
4. **Temporal aggregation of reservations**
5. **Selection of the most interpretable findings**
6. **Transformation of those findings into a narrative visualization**

The final story was designed to prioritize **clarity, interpretability, and communication of business-relevant patterns**, rather than exhaustive technical reporting.

## Tools Used

* **R / R Markdown** for exploratory analysis
* **Flourish** for interactive storytelling visualization

## Why This Project Matters

From a data science and analytics perspective, this project illustrates how exploratory analysis can be translated into a **clear decision-oriented narrative**.
Rather than presenting isolated charts, the repository shows how to move from raw booking data to a structured story that highlights differences in **demand behavior, pricing, cancellation risk, and stay composition**.

## How to Use

To review the project:

* Open the interactive story here: [Flourish Story](https://public.flourish.studio/story/3660287/)
* Inspect the analytical workflow in `hotel_bookings.Rmd`
* Explore the source data in `hotel_bookings.csv`

## Dataset

The analysis is based on the **Hotel Booking Demand** dataset, a widely used dataset for studying reservation patterns, cancellations, and hotel demand behavior.

## Author

**Víctor Suesta**
