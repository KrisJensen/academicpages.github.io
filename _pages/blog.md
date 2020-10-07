---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
redirect_from:
  - /blog
---

{% include base_path %}

<head>
<style>
a.blog:link {
  color: #003CA4;
  background-color: transparent;
  text-decoration: none;
}
a.blog:visited {
  color: #003CA4;
  background-color: transparent;
  text-decoration: none;
}
</style>
</head>

<p style="padding-bottom:-8px; margin-bottom:-8px">
<a style="font-weight:bold; font-size:3em" class="blog" href="http://KrisJensen.github.io/files/bias_blog.pdf">
Bayesian correction of systematic reviewer bias
</a>
</p>

{: style="text-align: justify" }
We rely increasingly on large-scale conferences for distributing our research, and conference presentations is even seen as a quality-stamp for early-career researchers.
Despite the importance this puts on fair selection processes, conference organizers unfortunately do not have unlimited resources for reviewing submissions.
This leads to stochasticity in the review outcome depending on whether a submission is assigned 'good' or 'bad' reviewers.
However, by writing down a Bayesian model that takes into account interactions between reviewers sharing submissions, we can explicitly remove systematic deviations from the mean across reviewers when assessing the quality of papers.