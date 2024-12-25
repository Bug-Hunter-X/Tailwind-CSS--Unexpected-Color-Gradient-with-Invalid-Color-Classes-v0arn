# Tailwind CSS Unexpected Color Gradient Bug

This repository demonstrates a potential issue in Tailwind CSS where using invalid color class values with the `bg-gradient-to-*` utility can lead to unexpected color gradients. The bug and a solution are provided.

## Bug
The issue arises when you attempt to use color classes that are not defined in your Tailwind CSS configuration or are misspelled within the `bg-gradient-to-*` utility. This can result in a color gradient different from the intended one or a complete rendering failure.

## Solution
The solution involves carefully verifying that the color classes used are valid and correctly spelled according to your Tailwind CSS configuration. Using the Tailwind CSS config file allows customization of the color palette to ensure the classes used are defined.

## Setup
1. Clone the repository.
2. Run `npm install` to install dependencies (if needed, adjust as per your setup).
3. Observe the buggy and fixed implementations in the respective files.
