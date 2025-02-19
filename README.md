# MongoDB Aggregation Pipeline Bug

This repository demonstrates a common bug encountered when using MongoDB's aggregation pipeline. The bug involves an incorrect pipeline causing unexpected results when grouping, sorting, and limiting documents. The solution shows the corrected pipeline for accurate aggregation.

## Bug

The original aggregation pipeline is flawed, resulting in inaccurate counts or unexpected sorting of grouped documents. The issue lies in the pipeline stages and their order. The `$project` stage in particular, needs to be checked for any errors, like incorrect field names or typos in field names which might cause the aggregation to fail or produce unexpected output.