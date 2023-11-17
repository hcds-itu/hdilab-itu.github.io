---
title: Human Data Interaction Lab
layout: home
description: "The Human Data Interaction Lab focuses on the human factors in the conception, use, and understanding of data. The lab functions as a venue for discussing matters related to human data interaction broadly and invites students and faculty to join forces to better understand these aspects."
# intro_image: "images/illustrations/pointing.svg"
# intro_image_absolute: true
# intro_image_hide_on_mobile: true
# show_call_box: true
image: "images/logo/logo-hdilab-og.png"
show_info_box: true
info_box_title: What is Human Data Interaction?
info_box_text: Human data interaction refers to the way that people interact with data in order to make sense of it, derive insights from it, and ultimately make decisions based on it. It involves the use of various tools, technologies, and techniques to facilitate this interaction, such as data visualization tools, data analysis software, machine learning algorithms, and novel interfaces and techniques for interacting with these tools.
---

# Human Data Interaction Lab
The Human Data Interaction Lab focuses on the human factors in the conception, use, and understanding of data. The lab functions as a venue for discussing matters related to human data interaction broadly and invites students and faculty to join forces to better understand these aspects.

<!-- ## What is Human Data Interaction?
Human data interaction refers to the way that people interact with data in order to make sense of it, derive insights from it, and ultimately make decisions based on it. It involves the use of various tools, technologies, and techniques to facilitate this interaction, such as data visualization tools, data analysis software, machine learning algorithms, and novel interfaces and techniques for interacting with these tools. -->

## People and affiliated research groups
About twenty [people](/people) are affiliated with the lab, some of which are also members of the [hcds](https://hcds.itu.dk) research group. [Reach out](mailto:hdilab@o365team.itu.dk) if you're interested in becoming a part of the lab!

## Events
We run two different kinds of events in the lab: Data Jams and research events. 

Data Jams are particularly relevant for ITU students. Please see our [overview of Data Jams](/data-jams) for more on this.

Research events, such as talks by visiting researchers often have broader appeal.



<div class="row research-events">
<h2>Upcoming Research Events</h2>
<dl>
  {% assign featured_research-events = site.research-events | where_exp: "post", 'post.event-date-start >= site.time'  | sort: "post.event-date-start"  %}
  {% for research-event in featured_research-events  limit:3 %}
    <!-- <div class="col-12 col-md-12 mb-12"> -->
    <!-- <div class="researchevent researchevent-summary researchevent-summary-large"> -->
      <!-- <div class="researchevent-content col-md-6"> -->
        <!-- <h2 class="researchevent-title"> -->
          <dt><a href="{{ research-event.url | relative_url }}">{{ research-event.title }}</a></dt>
        <!-- </h2> -->
        <!-- <p> -->
          <dd>
            {{ research-event.event-date-start | date: '%B %d, %Y, starting at %H:%M' }}.
          </dd>
        <!-- </p> -->
        <!-- <p>{{ research-event.content | markdownify | strip_html | truncate: 300 }} -->
        <!-- </p> -->
        <!-- <p>
          <a href="{{research-event.signup-url}}" class="button btn-success">Signup</a>
          </p>
      </div>
      <div class="researchevent-content col-md-6">
          <p>
          <img style="width: 100%" src="{{ research-event.hero-image}}"/>
        </p>
      </div>
    </div>
  </div> -->
  {% endfor %}
</dl>
<a href="/research-events/">Overview of research events</a>.
</div>



