---
title: "Introducing Google SynthID"
date: 2023-09-01T19:53:33+05:30
draft: false
author: "Meghana Puttaswamy"
tags:
  - SynthID
  - Deepfake
  - AI
  - Image generation
image: /images/SynthID.PNG
description: "from google deepmind"
toc: 
---

Recently, I stumbled upon app that generates profession potraits developed on various selfies as input. I tried this and was amazed of the output(as you can know from the profile picture of this website). Soon, I was drowning in the thoughts of how accessible has generative AI become! The more the accessibility, the more the possibility of deepfakes.

**What are Deepfakes?**

Deepfakes, a portmanteau of "deep learning" and "fake," are computer-generated media that convincingly replace the likeness of a person in an existing image or video with someone else's likeness. This is made possible through the power of artificial intelligence (AI) and machine learning algorithms that can learn and mimic the nuances of facial expressions, voice, and mannerisms.

The potential for deepfake misuse is vast. From creating misleading political propaganda to fabricating false narratives, the consequences can be severe. There are concerns about the erosion of trust, as people grapple with discerning between authentic and manipulated content.

The advacement in the research of generative AI should be in par with the technology to be protecting it. While reading through number of such blogs I started reading about Google Deepminds research on protecting AI generated images without ruining the picture quality.

---

**Introducing Google SynthID**

In the midst of these concerns, technology giant Google has stepped forward with an innovative solution—SynthID. SynthID is an AI-powered tool designed to detect and combat the proliferation of deepfakes. Leveraging advanced machine learning techniques, SynthID analyzes images and videos to identify signs of manipulation, helping to unmask synthetic identities and preserve the integrity of digital content.

**How SynthID Works**

SynthID embeds a digital watermark directly into the pixels of an image, making it imperceptible to the human eye, but detectable for identification.

With this tool, users can embed an imperceptible digital watermark into their AI-generated images and identify if Imagen was used for generating the image, or even part of the image.

---

**Watermarking**

Digital watermarks are added by SynthID's embedded watermarking technology directly into the pixels of AI-generated images, rendering them invisible to the human eye. The difference can be noticed in the above picture.

SynthID is designed in a way to not compromise image quality and retains the watermark to still be detectable even after modifying the image using filters, saving in different formats, cropping the picture.

---

**Identifying**

The tool provides three levels of confidence if the image has water mark or not and the thrid level of confidence is may be has a watermark.

---

Currently, the SynthID is available to limited Imagen and vertex AI users. I cannot wait for the software to be fully launched and try it first hand. I will definitely write a blog about my experience and first though! Stay tuned!!