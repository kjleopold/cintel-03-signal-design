# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
The dataset comes from a system that tracks operational metrics. Each row represents one observation and includes the number of requests, errors, and total latency in milliseconds.

### Signals
The original signals included error rate, average latency, and throughput, which help describe how the system is performing. I added a performance score that combines error rate and latency into one number to give a quick overall view of each observation.

### Experiments
I modified the code by creating a performance score using the original columns (requests, errors, and total latency) instead of the derived signals.

### Results
The output shows a performance score for each observation, with values ranging from about 94 to 97.5. Rows with fewer errors and lower latency have higher scores, while rows with more errors or higher latency have slightly lower scores

### Interpretation
This suggests that the system performs best when errors are low and response times are faster. The performance score makes it easier to quickly compare observations and spot when performance starts to drop, even if the differences are small.
