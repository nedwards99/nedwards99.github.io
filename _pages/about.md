---
layout: about
title: about
permalink: /
subtitle: #<a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.
show_header: false
_styles: |
  .about-top {
    display: flex;
    gap: 2rem;
    align-items: flex-start;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-bottom: 2rem;
  }

  .about-top .profile.float-right {
    float: none;
  }

  .about-top .profile {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-left: auto;
  }

  .about-top .social-top {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
    text-align: left;
  }

  .about-top .social-top .contact-icons {
    font-size: 1.8rem;
    display: flex;
    gap: 0.75rem;
  }

  .about-top .social-top .contact-icons a {
    margin: 0;
  }

  .about-top .social-top .contact-icons svg,
  .about-top .social-top .contact-icons img {
    width: 2rem;
    height: 2rem;
  }

  .about-top .social-top .contact-note {
    font-size: 0.85rem;
  }

  .profile figure {
    max-width: 220px;
    margin: 0 auto;
  }

  .profile img.rounded-circle,
  .profile img.rounded {
    border-radius: 47% / 40% !important;
    object-fit: cover;
  }

  .profile .profile-address {
    margin-top: 0.75rem;
    line-height: 1.4;
    text-align: center;
    display: inline-block;
    padding: 0.25rem 0.75rem;
    background-color: rgba(0, 0, 0, 0.05);
    border-radius: 8px;
  }

  @media (max-width: 768px) {
    .about-top {
      flex-direction: column;
      align-items: center;
    }

    .about-top .social-top {
      align-items: center;
      text-align: center;
    }

    .about-top .social-top .contact-icons {
      justify-content: center;
    }

    .about-top .profile {
      margin-left: 0;
    }
  }

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: |
    <address class="profile-address">
      Kolingasse 14-16, 1090 Wien
    </address>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # displays social icons via _data/socials.yml

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

Hi! I'm Nick, a first-year PhD student at the University of Vienna supervised by [Sebastian Schuster](https://sebschu.com/). I'm interested in evaluating the abilities of LLM coding agents (see our work on [RExBench](https://rexbench.com/)), and developing more effective frameworks for human-agent collaboration.

Previously, I received a BA in Linguistics from the University of Cambridge, followed by an MSc in Speech & Language Processing from the University of Edinburgh. During my time at Edinburgh, I did research in emergent communication between neural networks with [Hannah Rohde](http://www.lel.ed.ac.uk/~hrohde/) and [Henry Conklin](https://hconklin.com/).

Get in touch here: `nicholas.edwards[æt]univie.ac.at`
