# Changelog

## Unreleased
- Added default `alloc` feature, and made the crate `#![no_std]`

## Version 0.1.2 (2020-02-21)

- Added `LineSpan::ending`, `LineSpan::range_with_ending`, and `LineSpan::as_str_with_ending`

## Version 0.1.1 (2020-02-16)

- Optimized `LineSpanIter`
- Added `str_to_range` and `str_to_range_unchecked`

## Version 0.1.0 (2020-02-10)

- Added `find_line_start`, `find_line_end`, and `find_line_range`
- Added `find_next_line_start`, `find_next_line_end`, and `find_next_line_range`
- Added `find_prev_line_start`, `find_prev_line_end`, and `find_prev_line_range`
- Added `LineSpans` trait, `LineSpanIter`, and `LineSpan`
