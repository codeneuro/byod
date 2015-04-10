# byod (bring your own data)

[![Join the chat at https://gitter.im/CodeNeuro/byod](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/CodeNeuro/byod?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## What you'll bring
Data, specifically, multivariate time series data. The data can come from anywhere: neuron responses, wearable sensors, climate financial records, user clicks, EEG channels. They just need to be time series. 

For small data sets
- We can convert from a variety of formats, including `npy` arrays, `mat` files, `csv`, or `text`.
- Data will either hosted as part of this repository (if sufficiently small), or on Amazon S3 at at s3://code.neuro/byod

For large data sets
- We recommend a flat binary format: a single file or multiple files, each containing contiguous bytes of fixed numerical type and (key, value) records of a fixed length, and a single JSON file specifying the number of keys, number of values, and numerical type of each. The JSON file can include additional fields with metadata.
- Data will be hosted on Amazon S3, at s3://code.neuro/byod

## What you'll do
Use open-source analysis and visualization tools to create the most interesting and revealing representations of your data. Work on your own, or in groups, on either your data, or someone else's.

## Where we'll put it
All analyses should be assembled as Jupyter notebooks, preferable in Python, but other languages welcome! Notebooks should be submitted as PRs to this repository. If you need to learn more about forking a repository and contributing to it, head over to the [gitgoing](http://github.com/CodeNeuro/gitgoing) tutorial!
