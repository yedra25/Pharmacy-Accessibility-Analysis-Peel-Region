# Pharmacy Accessibility Analysis in the Peel Region


## Overview

This project assesses spatial accessibility to pharmacy services in the Peel Region using the Two-Step Floating Catchment Area (2SFCA) method. The analysis focuses on identifying geographic disparities in access to essential health services, with particular attention to low-income populations.

## Objective

Pharmacies provide critical health services, yet their distribution is uneven across the Peel Region. This project aims to measure pharmacy accessibility at the dissemination area (DA) level and identify areas where low-income residents face reduced access due to distance and service availability.

## Data

Peel Region dissemination area boundaries (Statistics Canada, 2021)

Total population and low-income population (LIM-AT) from Census 2021

Pharmacy locations and employee counts from NAICS (2022), accessed via SimplyAnalytics

**Demand population:** 1,451,022 residents

**Aspatial group:** 111,380 low-income residents

## Methods

Applied the Two-Step Floating Catchment Area (2SFCA) method

Used a 5 km distance threshold to represent short-distance travel to pharmacies

**Step 1:** Calculated pharmacy supply-to-demand ratios using employee counts

**Step 2:** Computed accessibility index values for each dissemination area

Classified accessibility into low, medium, and high categories

## Key Findings

Pharmacies are concentrated in central Mississauga and Brampton

Medium accessibility areas serve the majority of residents and low-income populations

Caledon and Northern Brampton exhibit low accessibility despite substantial population presence

Low-income residents in low-access areas face compounded spatial and financial barriers

## Tools

ArcGIS Pro

Census and administrative datasets

Spatial accessibility modelling (2SFCA)

## Limitations

Use of dissemination area centroids may distort actual travel distances

Fixed distance thresholds do not account for real travel time or routes

Pharmacy capacity data only includes employee counts, not service hours or load

## Notes

This project was completed as part of GGR322 at the University of Toronto Mississauga.
The repository documents spatial accessibility methods and equity-focused GIS analysis.

### Recognition
This project was selected for inclusion in the Student Final Project Portfolio curated by the course instructor, highlighting exemplary student work from the course.

**Course portfolio (instructor GitHub):** https://population-health.github.io/GGR322/Final_portfolio.html
**Portfolio link:** https://population-health.github.io/GGR322/students/Arunima-Dey2.html

