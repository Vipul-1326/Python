Problem Description
Language: python
Category: enhancement
Difficulty: hard

## Problem Title

Parameter validation for audio filters

## Problem Description

Extend the existing `butterworth_filter` and `iir_filter` functions in the `audio_filters` module to include robust parameter validation:

- Raise `ValueError` for negative cutoff frequency, zero or negative sample rate, invalid order, non-numeric or multi-dimensional signals, and cutoff above Nyquist frequency.
- Ensure all invalid inputs are handled gracefully and tested.

When invalid parameters are provided, the functions must raise `ValueError` with a clear error message.

URL: https://github.com/Vipul-1326/Python.git
Commit: <latest-commit-or-example>
Issue: <example-issue-or-create-one-if-needed>
