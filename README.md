# Resource Management for Construction Projects

## Project Overview

This project aims to develop a Python program for tracking and managing resources in construction projects. The program focuses on ensuring the efficient utilization of materials, labor, and equipment, and identifying any potential inefficiencies.

## Project Objectives

* Track the allocation and usage of resources in construction projects.
* Ensure effective resource utilization and identify inefficiencies.
* Provide insights into resource consumption patterns and potential bottlenecks.

## Methodology

1.  **Data Import:** Resource usage data is imported from a CSV file, ensuring all necessary fields are present.
2.  **Resource Tracking:** Material usage and labor hours are tracked across tasks, ensuring resource availability for each task.
3.  **Resource Efficiency:** Material usage per task is calculated to identify overused or underused resources.
4.  **Resource Availability Check:** Upcoming tasks are assessed to ensure sufficient resource availability.
5.  **Visualization:** Bar charts are generated to compare resource usage across tasks, providing visual insights into resource allocation. Pie charts are also used for  visualizations.


## Implementation of Functions and Arguments

The program is implemented using Python and leverages libraries such as Pandas and Matplotlib for data manipulation and visualization. Key functions include:

*   **`track_resources(task_id, resource_type, amount_needed)`:**

    *   **Arguments:**
        *   `task_id`: The ID of the task.
        *   `resource_type`: The type of resource (e.g., 'concrete', 'labor').
        *   `amount_needed`: The amount of the resource needed for the task.
    *   **Functionality:** Tracks material usage and labor hours for a specific task and checks resource availability.
*   **`calculate_material_usage()`:**

    *   **Arguments:** None
    *   **Functionality:** Calculates material usage per task.
*   **`check_resource_availability()`:**

    *   **Arguments:** None
    *   **Functionality:** Checks resource availability for upcoming tasks.
*   **`create_resource_charts(resource_type)`:**

    *   **Arguments:**
        *   `resource_type`: The type of resource for which to create the chart.
    *   **Functionality:** Generates bar charts or pie charts for visualizing resource usage.

## Usage

1.  Import the necessary libraries.
2.  Load the resource usage data from the CSV file.
3.  Utilize the functions to track resources, calculate material usage, check resource availability, and generate visualizations.

## Results and Insights

The program provides insights into resource consumption patterns, potential bottlenecks, and areas for improvement in resource management. Visualizations aid in understanding resource allocation across tasks.

## Visualization

### Bar Chart

![Bar Chart of Resource Usage](bar_chart.png)


### Pie Chart

![Pie Chart of Resource Usage](pie_chart.png)


## Conclusion

This project demonstrates the application of Python for resource management in construction projects. The developed program offers a foundation for further enhancements and customization to address specific project needs.

## Author

*   Rahatun Nesa Priti

## Acknowledgments

*   Google Colab
*   Pandas library
*   Matplotlib library
