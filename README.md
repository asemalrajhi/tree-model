# Tree Condition Analysis Model

This repository hosts the exported Teachable Machine model (TensorFlow.js) used to analyze the condition of trees/plants.  
The model is served via GitHub Pages so it can be loaded directly in browser-based web apps.

## Usage

1. The `model.json`, `metadata.json` and weight file(s) are placed here.
2. Load the model from the URL:  
   `https://asemalrajhi.github.io/tree-model/model.json`
3. Use TensorFlow.js in a web page to predict on uploaded images.
4. Results can be sent to a Google Apps Script backend for email/notification/storage.
