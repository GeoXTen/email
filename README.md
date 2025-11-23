# Email Dot Generator

A simple web application that generates all possible email variations with dots inserted in the local part of an email address.

## Features

- Generates all possible combinations of dot placements in email addresses
- Copy emails to clipboard with one click
- Responsive design that works on desktop and mobile devices
- No server-side processing - everything runs in the browser

## How to Use

1. Enter your email address in the input field
2. Click "Generate Email" or press Enter
3. Browse through all the generated variations
4. Click "Copy" next to any email to copy it to your clipboard

## Deployment

This application can be deployed to Cloudflare Pages directly from this repository.

## Technical Details

The application is built with pure HTML, CSS, and JavaScript with no external dependencies. The algorithm uses binary representation to generate all possible combinations of dot placements while respecting Gmail's rules for dot placement.