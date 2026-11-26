---
title: Hello World — A Little About Me
description: Welcome to my website
slug: hello-world
date: 2027-11-26 00:00:00+0000
image: cover.jpg
categories:
  - About Me
tags:
  - Personal
  - Career
  - Darwin
  - Technology
weight: 1 # You can add weight to some posts to override the default sorting (date descending)
---

Hi, welcome to my little corner of the internet!

I'm **Rene**, a software developer currently based in **Darwin, Northern Territory, Australia**.

## My Professional Journey

I hold a Master of Software Engineering from Fudan University and have over eight years of commercial software development experience, primarily in the financial technology industry.

Before moving to Australia, I worked as a Senior Engineer at **Green Dot Corporation**, a US-based financial technology company, developing and maintaining banking applications used by millions of customers across the United States.

### Technical Skills

My technical experience includes:

- **Frontend:** React, Angular, JavaScript, HTML5 and CSS3
- **Backend:** C#, .NET, ASP.NET MVC and Web API
- **System Integration:** REST APIs and third-party services
- **Database:** SQL Server
- **Development Tools:** GitHub, TeamCity, JIRA and Confluence
- **Other Areas:** WordPress, PHP, application support, testing and troubleshooting

I enjoy solving practical problems, exploring new technologies and understanding how different systems work together.

## A New Chapter in Darwin

In December 2025, I moved from Shanghai to Darwin, starting a new chapter in both my personal and professional life.

Since arriving in Darwin, I have had opportunities to work on local software projects, including healthcare application testing, data migration and business system integration.

Starting again in a new country has brought both challenges and opportunities. I have enjoyed meeting people from different backgrounds, learning about Australian culture and becoming part of the local community.

I hope to continue building my career in the Northern Territory and use my technical skills to make a meaningful contribution to the place I now call home.

## About This Website

This website is a space where I share my professional experiences, technical knowledge, personal interests and thoughts along the way.

> Photo by [Pawel Czerwinski](https://unsplash.com/@pawel_czerwinski) on [Unsplash](https://unsplash.com/)

<div id="browserAgent">Loading browser agent information...</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
  // Function to fetch User-Agent from the Cloudflare Worker
  function fetchUserAgent() {
    fetch('https://browser.rene-hu.workers.dev/')
      .then(function(response) {
        return response.text();
      })
      .then(function(data) {
        document.getElementById('browserAgent').textContent = data;
      })
      .catch(function(error) {
        console.error('Error fetching the User-Agent:', error);
        document.getElementById('browserAgent').textContent = 'Failed to load browser agent information.';
      });
  }

  // Call the fetchUserAgent function when the document is ready
  fetchUserAgent();
});
</script>
