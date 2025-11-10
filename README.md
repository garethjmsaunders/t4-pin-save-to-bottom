# Fix T4 Edit Action Bar

This userstyle pins the **Save / Cancel / Delete** action bar to the bottom of the viewport in the **TerminalFour content edit interface** at the University of St Andrews. It ensures the form actions remain visible while scrolling through long content forms.

## Overview

When editing a content item in T4, the action buttons normally appear at the bottom of the form.  

This userstyle keeps them fixed to the bottom of the browser window so you can save or cancel without needing to scroll.

## Installation

1. Install the **Stylish** or **Stylus** browser extension.  
   - Chrome: [Stylus on Chrome Web Store](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)  
   - Firefox: [Stylus on Mozilla Add-ons](https://addons.mozilla.org/en-GB/firefox/addon/styl-us/)
2. Create a new style.
3. Paste in the CSS from this repository.
4. In the **Domains** field, enter the URL for your T4 server.
5. Save and enable the style.

## Features

- Pins `.form-actions.text-right` to the bottom of the viewport.
- Adds a white background, subtle border, and drop shadow for contrast.
- Maintains button layout and alignment.
- Adds padding to page content to prevent overlap.
- Removes transforms and overflow clipping that can interfere with fixed positioning.

## Notes

- Designed for T4 v8 content-edit views on the St Andrews live authoring server.
- May need minor adjustments if future T4 updates change class names or layout structure.
- To disable temporarily, toggle the style off in the Stylish / Stylus extension.

## Author

Created by **Gareth J M Saunders**  
Digital Communications Team  
University of St Andrews