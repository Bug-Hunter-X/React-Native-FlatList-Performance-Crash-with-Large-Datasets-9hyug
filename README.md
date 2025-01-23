# React Native FlatList Performance Issue

This repository demonstrates a common performance issue encountered when using the `FlatList` component in React Native with very large datasets. The application crashes or becomes unresponsive due to excessive memory consumption.

## Problem

Rendering a large number of items in a `FlatList` can lead to performance problems, including crashes and freezes. React Native's default rendering behavior isn't optimized for incredibly large lists.

## Solution

The provided solution demonstrates how to use techniques like `windowSize` and `initialNumToRender` to improve rendering performance.  These options allow `FlatList` to render only a subset of items at a time, significantly reducing memory usage and improving the user experience.

## Usage

1. Clone the repository.
2. Run `npm install`.
3. Run the app on an emulator or physical device.  Observe the performance difference between the problematic and the solution implementation. 