---
width: expand
header:
  # image: header.jpg
  # background: "rgba(0, 0, 0, 0.5)"
  # color: light
  title: How can we help you?
  subtitle:
  # search: true
---

{% include categories.html 
  columns="3" 
  section="muted" 
%}

{% include faqs.html 
  multiple="true" 
  title="Frequently asked questions" 
  category="covid-faqs" 
  subtitle="Find answers to the most asked questions about Covid19." 
  section="muted" 
%}

{% include team.html 
  authors="sai, harsh, anish, kalpesh" 
  title="We are here to help" 
  subtitle="Our team is just an email away ready to answer your questions" 
  section="default" 
%}

{% include cta.html 
  title="Didn't find an answer?" 
  button_text="Contact Us" 
  button_url="/contact/" 
  subtitle="Have a feedback or query? Found an inaccurate FAQ?" 
  section="muted"
%}
