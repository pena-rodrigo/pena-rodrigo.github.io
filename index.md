---
---

# Pena Lab

Welcome to the Lab of Computational Neuroscience at the Department of Biological Sciences at Florida Atlantic University!

We are glad to have you visit our website and explore the world of computational neuroscience. As a cutting-edge research facility, we are dedicated to navigating the mysteries of the brain and pushing the boundaries of scientific discovery.

At our lab, we use computational models and advanced technologies to gain insights into the intricate workings of the brain. We work to develop innovative approaches that bridge the gap between theory and experiment.

Through our research, we aim to deepen our understanding of brain function, neural networks, and cognitive processes. By leveraging computational tools and methods, we strive to shed light on fundamental questions in neuroscience and contribute to the development of novel therapies for neurological disorders.

As you navigate through our website, you will find information about our ongoing projects, publications, and the talented individuals who make up our lab.

{% include section.html %}

{% capture text %}

Our research focuses on the computational modeling of ion channels, synapses, neurons, networks, and systems, and the interactions across various spatial scales. By capturing the essence of neural activity, we decode the mechanisms underlying brain function, shed light on information processing, and explore aspects of neurological disorders.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/res.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% include section.html %}

{% capture text %}

The Pena Lab hosts training events and scientific workshops focused on computational neuroscience methods, collaborative learning, and practical applications for modern neuroscience research.

Our featured upcoming event is the School for Computational Applications in Neuroscience (SCAN), a short school covering connectomics, network analysis, large-scale simulation, AI, bioinformatics, and emerging computational approaches.

{%
  include button.html
  link="workshops/"
  text="View upcoming workshops"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/neurons_front.jpeg"
  link="workshops/"
  title="Workshops and Training"
  text=text
  flip=true
%}
