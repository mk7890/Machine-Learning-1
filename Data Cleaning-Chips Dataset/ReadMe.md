# Data Cleaning (Semiconductor Chips Dataset)
# Overview

The data comes from [CHIP Dataset](https://chip-dataset.vercel.app/).

- [Moore's Law](https://www.synopsys.com/glossary/what-is-moores-law.html#:~:text=Definition,as%20E%20%3D%20mc2).)
- [Wikipedia - Moore's Law](https://en.wikipedia.org/wiki/Moore%27s_law)

> Moore's law is the observation that the number of transistors in a dense integrated circuit (IC) doubles about every two years. Moore's law is an observation and projection of a historical trend. Rather than a law of physics, it is an empirical relationship linked to gains from experience in production.

Paper for citation: [Summarizing CPU and GPU Design Trends with Product Data](https://arxiv.org/abs/1911.11313)

Note that the authors prohibit resharing the dataset, we have a simple summary. You can easily download the latest full dataset at the bottom of: <https://chip-dataset.vercel.app/>

If the data downloaded from the above website has inconsitencies with what is required to answer the below questions, feel free to use the data provided in this starter folder. 

# Tasks Performed

1. Explore the missingness in the dataset for categorical and numerical data
2. Develop a strategy to deal with the missing values, i.e deletion, imputation by mean or mode etc, whilst providing rationale for your approach.
3. Drop non-consequntial fields
4. Transform temporal data to their corrrect format (date time) 
5. Perfom a full EDA and demonstrate the validity of the following assumptions 
> - Moore's Law still holds, especially in GPUs.
> - Dannard Scaling is still valid in general.
> - CPUs have higher frequencies, but GPUs are catching up.
> - GPU performance doubles every 1.5 years.
> - GPU performance improvement is a joint effect of smaller transistors, larger die size, and higher frequency.
> - High-end GPUs tends to first use new semiconductor technologies. Low-end GPUs may use old technologies for a few years.
> - Process Size for Intel, AMD and Nvidia lies in comparatively lower range than for ATI and other vemdors
> - TSMC makes the highest number of chips in the world

6. Calculate and visualized the correlation among the features
7. Perfom the correct encoding for your data, in readiness for modelling. 
