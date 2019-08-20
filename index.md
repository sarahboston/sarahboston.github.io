---
title: ## Welcome
layout: page
feature_image: "https://sarahboston.github.io/assets/images/IMG_3853.JPG"
feature_text: |
  ## Mini Lab
---

Welcome to the Cat laboratory! We study the Earth, the ocean, and space. Testing. Testing

$researchgate-color: #00d09d;
$google-scholar-color: #4788ee;

.ai-researchgate {
  padding: 5px;
  @include social-media-icon($researchgate-color, $icon-transition-time);
}

.ai-google-scholar {
  padding: 5px;
  @include social-media-icon($google-scholar-color, $icon-transition-time);
}


{% include social-media-icon.html id="google=scholar"};


{% include icon.html id="cv" title="twitter" %}
{% include button.html icon="cv" text="Google Scholar" link="https://scholar.google.com/citations?user=BlvnMOgAAAAJ&hl=en&oi=ao" color="#0d94e7" width=20%}
{% include button.html icon="twitter" text="Test" link="https://scholar.google.com/citations?user=BlvnMOgAAAAJ&hl=en&oi=ao" color="#0d94e7" width=50%}