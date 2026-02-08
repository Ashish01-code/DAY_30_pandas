# DAY_30_pandas
Topics Covered
1. Creating New Columns

Derived features created from existing data.

Examples:

Total or adjusted marks

Pass / Fail indicators

Bonus or penalty calculations

Purpose:

Convert raw values into meaningful signals

2. apply() Function

Used to apply custom logic to each value in a column.

Used for:

Conditional logic

Mathematical transformations

Mapping values to categories

This is essential for preprocessing before ML training.

3. Lambda Functions

Short inline functions used with apply().

Why used:

Clean and readable

Fast feature transformations

Common in ML preprocessing pipelines

4. Binning (Discretization)

Converting continuous numerical values into categories.

Example:

Marks → Low / Average / Good / Excellent

Why important:

Some ML models perform better with categorical data

Helps reduce noise

Improves interpretability

5. ML Perspective (Conceptual)

Raw marks alone = weak learning signal

Engineered features (grade, level, result) = strong signal

Feature engineering helps reduce overfitting and improve generalization
