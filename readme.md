## Introduction

Insertion Sort is a simple, comparison-based sorting algorithm. It builds the final sorted array (or list) one item at a time. The algorithm is adaptive, stable, and works similar to how one might sort a hand of playing cards.

## How It Works

1. Start from the second element (assume the first element is sorted).
2. Compare the current element with the previous elements.
   - If the current element is smaller than the previous element, compare it with the elements before the previous element.
   - Continue this process until you reach an element smaller than the current element or reach the start of the array.
   - Insert the current element in the correct position so that the elements before are smaller than the current element.
3. Repeat the process for each of the elements in the list.