---
layout: archive
permalink: /publications/
author_profile: true
---
<h1 style="border-bottom: 2px solid;">Research Interest</h1>

My research focuses on Natural Language Processing (NLP) and Machine Learning, with an emphasis on building practical, interpretable, and efficient AI systems. My key areas of interest include:
- Low-Resource & Multilingual NLP: Developing NLP solutions for underrepresented languages, particularly Bangla, focusing on sentiment analysis and social media text mining.
- Explainable AI (XAI) & Transformers: Fine-tuning models like BanglaBERT and applying techniques like LIME and SHAP to ensure model transparency and trustworthiness.
- Applied ML & Deployment: Bridging the gap between research and production by optimizing (e.g., ONNX) and deploying scalable ML systems using FastAPI and Docker.


<!-- My broad research interests lie in the fields of Computer Vision and Natural Language Processing. Some of the specific areas I am interested include:
- Adversarial Machine Learning and Anomaly Detection – studying adversarial attacks and defenses to improve the robustness and security of machine learning models.
- Multilingual and Low-Resource NLP – developing methods to efficiently utilize resources for low- and zero-resource languages.
- Multimodal Learning – integrating text, image, audio, and video modalities for improved representation and understanding.
- Generative Models – applying models such as GANs and diffusion models for intra-modal and cross-modal tasks, including high-quality image reconstruction and synthesis. -->
<!-- - Cross-Modal Learning, Integrating Visual, Textual, and Acoustic Data for Advanced AI Systems -->

<br>
<h1 style="border-bottom: 2px solid;">Research and Publications</h1>
{% if site.author.googlescholar %}
  <div class="wordwrap"><a href="https://scholar.google.com/#" style="color: #990033;" target="_blank"></a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
