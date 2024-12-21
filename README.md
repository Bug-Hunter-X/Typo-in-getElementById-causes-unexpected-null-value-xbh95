# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle bug that can occur in HTML/JavaScript code. The bug stems from a simple typo in the `getElementById` method used to access an HTML element.  This typo leads to unexpected behavior, as the incorrect method returns `null`, causing subsequent operations to fail silently.

## Bug Description

The provided HTML file attempts to change the text content of a div element.  However, a typo in the `getElementById` method (`getElementByIdx` instead of `getElementById`) results in the JavaScript code failing to find the element.  This results in the text not being updated and the `else` block, logging the error message, being executed instead.