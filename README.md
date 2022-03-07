# Bias in Automated Image Colorization: Metrics and Error Types

This repository contains examples of colorized images. All images are colorized using the `artistic` model from DeOldify.

## Images
For each reason, we selected the image with the highest value. Images of humans are examples that were not chosen through specific values.

Ground Truth | Colorized | Image ID | Reason | Value | 
---|---|---|---|---
![](images/00000136_human_ground_truth.jpg)             | ![](images/00000136_human_colorized_file.jpg)             | 00000136 | human               | -
![](images/00002262_human_ground_truth.jpg)             | ![](images/00002262_human_colorized_file.jpg)             | 00002262 | human               | -
![](images/00005581_third_bottom_diff_ground_truth.jpg) | ![](images/00005581_third_bottom_diff_colorized_file.jpg) | 00005581 | third_bottom_diff   | 77.414
![](images/00006607_human_ground_truth.jpg)             | ![](images/00006607_human_colorized_file.jpg)             | 00006607 | human               | -
![](images/00006700_third_top_diff_ground_truth.jpg)    | ![](images/00006700_third_top_diff_colorized_file.jpg)    | 00006700 | third_top_diff      | 69.757
![](images/00012765_center_diff_ground_truth.jpg)       | ![](images/00012765_center_diff_colorized_file.jpg)       | 00012765 | center_average_diff | 81.819
![](images/00023303_human_ground_truth.jpg)             | ![](images/00023303_human_colorized_file.jpg)             | 00023303 | human               | -
![](images/00024091_golden_dots_diff_ground_truth.jpg)  | ![](images/00024091_golden_dots_diff_colorized_file.jpg)  | 00024091 | gold_dots_diff      | 62.353
![](images/00024474_human_ground_truth.jpg)             | ![](images/00024474_human_colorized_file.jpg)             | 00024474 | human               | -
![](images/00024567_third_left_diff_ground_truth.jpg)   | ![](images/00024567_third_left_diff_colorized_file.jpg)   | 00024567 | third_left_diff     | 75.708

## Structure
### `images/`
Contains two files for each image and a `values.md` that explains why the image was chosen.
