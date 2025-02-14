---
layout: page
title: "OptiDraft"
description: A champion drafting and recommender system for League of Legends
importance: 1
category: "Data Science"
img: /assets/img/OptiDraft-cover.png
---

### Quick Summary

- Spearheaded a 5-member team in architecting a character recommender system for League of Legends
- Built a robust ETL pipeline processing 36K API-sourced match records with fault tolerance and memory optimization
- Created synergy metrics for team dynamics, achieving 20% win-rate improvement through fine-tuned models (logistic regression, random forest, MLP)
- Launched [public web interface](https://optidraft.github.io/optidraft/) providing real-time draft suggestions

Tools: Python (Scikit-learn, Pandas, Matplotlib), PostgreSQL, Jupyter Notebook, GitHub

### Web Interface

<iframe src="https://optidraft.github.io/optidraft/" width="100%" height="600px">
  <p>Your browser does not support iframes. You can <a href="https://optidraft.github.io/optidraft/">click the link here</a>.</p>
</iframe>

<script>
  function reloadIframe() {
      var iframe = document.getElementById('pdfViewer');
      iframe.src = iframe.src;
  }

  function checkIframeLoaded() {
      var iframe = document.getElementById('pdfViewer');
      var iframeDoc = iframe.contentDocument || iframe.contentWindow.document;

      if (iframeDoc.readyState == 'complete') {
          if (iframeDoc.body.innerHTML.length == 0) {
              console.log("Iframe failed to load, attempting reload...");
              reloadIframe();
          } else {
              console.log("Iframe loaded successfully");
          }
      } else {
          console.log("Iframe still loading...");
          setTimeout(checkIframeLoaded, 1000);
      }
  }

  window.onload = checkIframeLoaded;
</script>

For the best user experience, please open the link on a desktop: [https://optidraft.github.io/optidraft/](https://optidraft.github.io/optidraft/)  
For more detailed project information, please visit the GitHub repo: [https://github.com/optidraft/lol-draft-pick](https://github.com/optidraft/lol-draft-pick)
