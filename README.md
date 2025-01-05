# Inconsistent CSS :hover Behavior Across Browsers

This repository demonstrates a subtle bug related to the `:hover` pseudo-class in CSS and inconsistencies observed across different web browsers. The primary issue lies in the transition effect not being applied consistently, resulting in a jarring or non-existent change in background color when hovering over elements. 

The `bug.css` file shows the problematic CSS. The `bugSolution.css` offers a potential fix.

## Bug Description
The expected behavior is a smooth transition of the background color on hover. However, certain browsers may exhibit abrupt changes or lack of transition altogether.

## Solution
The solution attempts to address browser inconsistencies by ensuring the transition property is correctly applied and accounting for potential vendor prefixes.