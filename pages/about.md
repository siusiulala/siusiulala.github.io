---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

<div class="row">
{% include about/skills.html title="Mobile Application Development" source=site.data.mobile-skills %}
{% include about/skills.html title="Desktop Application Development" source=site.data.app-skills %}
{% include about/skills.html title="Backend Service Development" source=site.data.be-skills %}
</div>
<div class="row">
{% include about/skills.html title="Database" source=site.data.db-skills %}
{% include about/skills.html title="Media" source=site.data.media-skills %}
{% include about/skills.html title="Cloud Services" source=site.data.saas-skills %}
</div>

<div class="row">
{% include about/timeline.html title="Edu" source=site.data.timeline-edu %}
{% include about/timeline.html title="Experance" source=site.data.timeline %}
</div>
