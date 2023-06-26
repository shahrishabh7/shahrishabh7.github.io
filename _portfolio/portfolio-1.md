---
title: "AirBNB HostAI"
excerpt: "AI-driven platform built to power short-term rental hosts"
collection: portfolio
---

HostAI brings generative AI to the pocket of Airbnb hosts. We built a content generation feature that writes compelling Airbnb, VRBO, and Booking.com listings that convert. We also built a ground team tool that allows hosts to seamlessly hire their ground team (cleaners, handymen, etc.). We built our backend using [LangChain](https://python.langchain.com/docs/get_started/introduction.html) and [Pinecone](https://www.pinecone.io/?utm_term=pinecone%20database&utm_campaign=Brand+-+US/Canada&utm_source=adwords&utm_medium=ppc&hsa_acc=3111363649&hsa_cam=16223687665&hsa_grp=133738612775&hsa_ad=582256510975&hsa_src=g&hsa_tgt=kwd-1628011569824&hsa_kw=pinecone%20database&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQjw7uSkBhDGARIsAMCZNJtJTdGWA3bWO5fknf1cNbMsH-CM0juQHkFwfd4z74_bb3gaIvsTut4aAlkkEALw_wcB) (vector database), powered by OpenAI's ['text-davinci-003' model](https://platform.openai.com/docs/models/overview). We built out frontend using [React](https://react.dev/) and [Material-UI](https://mui.com/).

Check it out below:
[HostAI](https://host-ai-landing.vercel.app/)

<iframe width="560" height="315" src="https://www.youtube.com/embed/oFWh0JNBZNM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

We used [SQLAlchemy](https://www.sqlalchemy.org/) to aggregate model output data, identify prompting weaknesses, and finetune the algorithm.

I worked on this project with [Nithanth Ram](https://github.com/Nithanth). You can find it [here](https://github.com/shahrishabh7/listing-rater-frontend).