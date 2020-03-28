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
  category="presale" 
  subtitle="Find quicke answers to frequent pre-sale questions asked by customers" 
  section="muted" 
%}

{% include team.html 
  authors="evan, john, sara, alex, tom, daniel" 
  title="We are here to help" 
  subtitle="Our team is just an email away ready to answer your questions" 
  section="default" 
%}

{% include cta.html 
  title="Didn't find an answer?" 
  button_text="Contact Us" 
  button_url="/contact/" 
  subtitle="Get in touch with us for details on setup and additional custom services pricing" 
  section="muted"
%}
