---
layout: post
title: A Call for Blog Posts
tags: [proposal, call]
authors: Bubeck, Sebastien, Microsoft; Dobre, David, Mila; Gauthier, Charlie, Mila; Gidel, Gauthier, Mila; Vernade, Claire, DeepMind

---

# Motivations

The Machine Learning community is currently experiencing a
[reproducibility
crisis](https://neuripsconf.medium.com/designing-the-reproducibility-program-for-neurips-2020-7fcccaa5c6ad)
and a reviewing crisis . Because of the highly competitive and noisy
reviewing process of ML conferences , researchers have an incentive to
oversell their results, slowing down the progress and diminishing the
integrity of the scientific community. Moreover with the growing number
of papers published and submitted at the main ML conferences , it has
become more challenging to keep track of the latest advances in the
field.

Blog posts are becoming an increasingly popular and useful way to talk
about science . They offer substantial value to the scientific community
by providing a flexible platform to foster open, human, and transparent
discussions about new insights or limitations of a scientific
publication. However, because they are not as recognized as standard
scientific publications, only a minority of researchers manage to
maintain an active blog and get visibility for their efforts. Many are
well-established researchers ([Francis Bach](https://francisbach.com/),
[Ben Recht](https://www.argmin.net/), [Ferenc
Huszár](https://www.inference.vc/), [Lilian
Weng](https://lilianweng.github.io/lil-log/)) or big corporations that
leverage entire teams of graphic designers designer and writers to
polish their blogs ([Facebook AI](https://ai.facebook.com/blog/?page=1),
[Google AI](https://ai.googleblog.com/),
[DeepMind](https://deepmind.com/blog),
[OpenAI](https://openai.com/blog/)). As a result, the incentives for
writing scientific blog posts are largely personal; it is unreasonable
to expect a significant portion of the machine learning community to
contribute to such an initiative when everyone is trying to establish
themselves through publications.

Our goal is to create a formal call for blog posts at ICLR to
incentivize and reward researchers to review past work and summarize the
outcomes, develop new intuitions, or highlight some shortcomings. A very
influential initiative of this kind happened after the second world war
in France. Because of the lack of up-to-date textbooks, a collective of
mathematicians under the pseudonym Nicolas Bourbaki , decided to start a
series of textbooks  about the foundations of mathematics. Their modern
—at the time— structuralist take on mathematics had a long lasting
impact that continues to influence the mathematics community of today.

# Our Idea: Blog post Conference Track

Due to the large diversity of topics that can be discussed in a blog
post, we decided to restrict the range of topics for this call for blog
posts. We identified that the blog posts that would bring to most value
to the community and the conference would be posts that distill and
discuss *previously published papers*.

## Call for blog posts on papers previously published at ICLR

The call for blog post would take the following form:

-   Write a post about a paper previously published at ICLR, with the
    constraint that one cannot write a blog post on work that they have
    a conflict of interest with. This implies that one cannot review
    their own work, or work originating from their institution or
    company. We want to foster productive discussion about *ideas*, and
    prevent posts that intentionally aim to help or hurt individuals or
    institutions.

-   Blogs will be peer-reviewed (double-blind, see
    Section <a href="#sub:sub_process" data-reference-type="ref" data-reference="sub:sub_process">2.5</a>)
    for quality and novelty of the content: clarity and pedagogy of the
    exposition, new theoretical or practical insights,
    reproduction/extension of experiments, etc.

-   The posts will be published under a unified template (see
    Section <a href="#sub:sub_format" data-reference-type="ref" data-reference="sub:sub_format">2.4</a>
    and
    Section <a href="#sub:sub_process" data-reference-type="ref" data-reference="sub:sub_process">2.5</a>)
    and hosted on the conference website or our own Github page.

## Positive Impact for the Community

We believe having this call for blog posts as a conference track would
increase the posts’ visibility, impact, and credibility, while
simultaneously providing benefits to the conference.

-   *Adoption*: we think that, with the conference’s stamp, such a
    format will be more broadly recognized and adopted by the community.

-   *Accessibility*: maintaining a blog is time consuming , and requires
    many blog posts to gain a stable following. By allowing researchers
    to publish a single post, we will permit occasional blog writers to
    publish their ideas, something that is relatively impossible right
    now. Moreover, it will make this format accessible to more
    independent/junior blog writers that do not have a company or a
    research lab to support them.

-   *Synchronization*: the fast evolving field of ML advances at the
    paces of its conferences. By following the same pace the blog posts
    will add value and momentum to the conference. It will benefit from
    the same advantages of conferences with respect to scientific
    journals: faster publication process and cross-fertilization of
    ideas.

## Positive Impact for the Conference

We develop the potential positive impact of a blog post track for the
conference itself:

-   Increases the value of the papers submitted to ICLR: blog posts will
    discuss previously published papers, thus increasing their
    visibility and quality.

-   Incentivizes researchers to submit their best research to ICLR: high
    quality work will likely get highlighted in future years in a blog
    post.

-   Improves reproducibility and transparency: the blog post track will
    identify and publicly document pitfalls and "tricks" that were not
    clearly communicated in the original publication.

-   Provides a scientific value by itself: such blog posts will
    reproduce and extend results of previously published papers. They
    will distill important theoretical and practical ideas improving
    their adoption and impact.

-   Tests of time: this track will provide a sort of crowd-sourced test
    of time at a shorter timescale than the current test of times
    awards.

-   Promotes accessibility: because many of this track’s blog posts will
    vulgarize past content, this track will make the conference broadly
    more accessible (to students, non-natives, and, more generally,
    non-experts in the field).

## Submission Format

Our goal is to avoid heavily engineered, professionally-made
blog-posts[1], to entice ideas and clear writing rather than dynamic
visualizations or embedded javascript engines.

As a result, we restrict submissions to the Markdown format. We believe
this is a good trade-off between complexity and flexibility. Markdown
enables users to easily embed media such as images, gifs, audio, and
video as well as write mathematical equations using MathJax, without
requiring users to know how to create HTML web pages. This (mostly)
static format is also fairly portable; users can download the blog post
without much effort for offline reading or archival purposes. More
importantly, this format can be easily hosted and maintained through
GitHub.

## Submission Process

A full copy of the track’s blogs will always be publicly available as a
GitHub repository [(mock-up
link)](https://github.com/bourbaki-blogchain/bourbaki-blogchain.github.io).
Entrants will need to fork this repository and make their fork private.
Should they fail to do so, their submission will be rejected as it
breaches the double-blind review process. Since this is a full fork,
they will be able to view their own copy of the blog. This means that
they will be able to see exactly how their post will look and behave in
the main website.

In their fork, they will add their new blog post along with any media
files it might require. To submit a blog post, the entrants will zip
their fork (but not before stripping it of the author’s names), and
submit it to our OpenReview venue. Once accepted, entrants will
de-anonymize their post, make their fork public again, and make a GitHub
Pull Request to the main blog, allowing us to pull in their new blog
post in a transparent way.

A temporary mock-up of the blog website is available:
<https://bourbaki-blogchain.github.io//about/>. Once the submission
period has ended, the GitHub repository of our track will be temporarily
made private for the duration of the conference, allowing the conference
to host the website. After the conference, the GitHub repository will be
made public again to allow viewers to fork and download its contents.

## The potential Pitfalls of our Blog Post Track

In this section we identify potential issues arising with such a track
and explain how to mitigate them:

1.  *Adversarial Blog Posts*: Since the guidelines are to write a blog
    post on a previously published paper, one may expect some researcher
    to try to use bad faith arguments to criticize a concurrent paper
    through one of these blog post. We do not think this will happen,
    because these blog posts will be public and thus researchers would
    discredit themselves by using bad faith arguments.

2.  *Too many/few submissions*: As this is a new track, it may be
    difficult to predict the volume of submissions. The fact that there
    are currently many independent blog posts on the web is a good
    indicator that there will be positive interest. To get a better
    estimate of the volume of potential submissions, we intend to
    leverage social media to gauge the interest of the ML community in
    such a track; this will allow us to gather a large enough reviewing
    committee.

3.  *Reviewing*: Once again as this is a new track, it may be unclear
    how to judge blog posts during a review process. We will recruit a
    large reviewing committee and define clear guidelines for the
    reviewing process. Our primary focus will be on the originality of
    the perspective and the novelty of the ideas, insights, and
    experiments. For instance, posts that reuse less content from the
    original paper (results, direct quotes) will be scored more
    favourably than those that use more.

4.  *Too many posts on the same paper*: We may mitigate this by only
    selecting a small numbers of blog posts on the same paper. This
    could actually be a strength since this can encourage discussion and
    highlight different perspectives on the same work. Moreover, we
    could explicitly state that we will have this hard limit (e.g.,
    accepting a maximum of 3 blog posts on the same paper) to entice
    researchers to submit blog posts on papers that have less
    visibility.

# Related Initiatives

We mainly address our difference with respect to
[Distill](https://distill.pub/), the [ML Retrospectives
Workshop](https://ml-retrospectives.github.io), a Tutorial Track, and
other workshops discussing alternative formats for publications.

#### Distill.

Created in 2016, [Distill](https://distill.pub/) is an online scientific
journal based on blog post publications. We address our differences with
respect to Distill: <span
class="sans-serif">\[ggi\]$\_{\\arabic{ggiCounter}}$:maybe more
here</span>

-   *Visualizations*: Blog posts should take advantage of the fact that
    they’re not paperbound, and use innovative visualisations. But the
    process of creating the intricate, dynamic visualisations associated
    with Distill posts is a daunting for most authors. Creating blog
    posts should be more easily accessible to newer authors and
    researchers. Sometimes, being able to embed videos and gifs is
    enough.

-   *Content*: Distill does not target the same type of content as our
    track. Distill aims at presenting new research, and at making this
    research more accessible. We want our blog post track to incentivize
    researchers to revisit and discuss on other researcher’s works, in a
    more natural way than scientific papers allow. Such a practice would
    undoubtedly be useful for the community, both as a short-term “test
    of time”, and also as a way to extract the key ideas from lengthy
    articles.

-   *Limited adoption by the community*: we believe that since Distill
    is not associated with a big conference track, its widespread
    adoption is hindered. This lack of association confines it to a
    small subset of the community that is already familiar with blog
    posts.

-   *Leveraging the momentum of the conference*: Distill describes
    itself as a scientific journal. A large amount of the publications
    in the ML community are conference papers. A blog post track that
    follows conferences would be better suited to follow the pace of the
    community.

#### ML-Retrospective Workshop.

A recurrent workshop in the ML community is the [ML Retrospectives
Workshop](https://ml-retrospectives.github.io) (NeurIPS 2019, 2020 and
ICML 2020). This workshop is a venue for researchers to talk about their
previous work in a more open and transparent way. More precisely,
emphasis has recently been put on addressing:

-   Flaws or mistakes in the paper’s methodology

-   Limitations in the applicability of the work

-   Changes in understanding or intuition

We share the ultimate goal of “making research more human”, but with a
completely different format. We believe that the constraint to write
about someone else’s work using natural language will channel fruitful
discussions and provide more visibility to previously published papers.

#### Tutorial Track.

We believe that our proposed blog post track differentiates itself from
a tutorial track because tutorials operate at different scales. On the
one hand, a tutorial regarding a whole topic (e.g. GANs, adversarial
examples, Random matrix theory in ML) contains a long talk, slides, and
potentially exercises to get familiar with the topics. It is usually
made by a team of expert researchers on the topic. On the other hand,
the call for blog posts we propose focuses on a single publication. It
regards a single paper that can concern a more precise and recent topic
(e.g., a specific paper that addresses mode collapse on GANs, a novel
technique to perform adversarial training, etc.) and could be written by
a single researcher (once again making it more accessible to junior
researchers).

#### Previous workshops on rethinking publication formats.

Recently, the [Rethinking ML Papers
Workshop](https://rethinkingmlpapers.github.io/) at ICLR 2021 fuelled
the discussion (see references therein for related past workshops). The
presenters discussed the importance of accessibility, web
demonstrations, visualization and blog posts (among others). One
particularly related discussion was the [talk by Lilian Weng
(time=4h25mins)](https://slideslive.com/38956531/beyond-static-papers-rethinking-how-we-share-scientific-understanding-in-ml)
on the usefulness of blog posts to get up-to-date with the field of ML.

In alignment with these initiatives, this new track is another step in
the direction of making research more human.

[1] Such as the “100+ hours” mentioned as a standard by the [Distill
guidelines](https://distill.pub/journal/)