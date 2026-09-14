# Assignment 1 — Python Fundamentals for Data Streaming

**Student:** Aslan Tulebay
**Group:** BDA-2403
**Notebook:** `Assignment_1_Asslan77.ipynb`

## Description

This project processes synthetic AITU campus shuttle events using Python. Each event contains a timestamp, route, bus ID, passenger count, speed, and status.

## Features

* Event validation
* Timestamp parsing
* Generator-based streaming
* JSON conversion
* FastAPI `POST /events` endpoint
* Occupancy category calculation
* Data analysis
* API testing

## Main Functions

* `validate_and_parse_event()`
* `get_occupancy_category()`
* `event_stream_generator()`
* `analyze_shuttle_data()`
* `process_event_endpoint()`

## Technologies

Python, Pandas, FastAPI, Pydantic, JSON, and Google Colab.

## Results

* Average passengers: **24.4**
* Maximum passengers: **30**
* STOPPED events: **1**
* Busiest event: **08:09, B02, 30 passengers**

## How to Run

1. Open `Assignment_1_Asslan77.ipynb` in Google Colab.
2. Run all cells from top to bottom.
3. Review the validation, API test, and analytics outputs.

## Limitation

The project uses a fixed synthetic dataset. A future improvement would be connecting it to a real-time streaming source.
