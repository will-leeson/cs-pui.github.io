---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home

header: 
    overlay_image: img/teach-research.png

---
<link rel="stylesheet" href="cspui.css">

![continuum of teaching and research](img/cs-pui-listing.jpg)

📣 For departments, if you would like to add a listing to this page, [please visit the **Add Listing** page](guide.html)
{: .notice-blue}

In 2017, I [wrote an article about finding academic happiness with **primarily-undergraduate institutions**](https://medium.com/bucknell-hci/the-jobs-i-didnt-see-my-misconceptions-of-the-academic-job-market-9cb98b057422). I continue to receive emails with the same  question: _how do I find these jobs?_ This listing of ads is meant to help navigate that muddy water. To see last year's list, [see the 20/21 version of this page](index-20.html).

This document does not contain many CS academic positions. It's intended for those who want to invest in teaching/mentorship with undergraduate students while still staying active in their scholarship. 

{% capture criteria %}
**Criteria:** the positions on this page should be...
- accessible to those with a Ph.D. in CS (or closely related field)
- Universities that identify as **primarily-undergraduate institutions**.
- Institutions that highly value teaching, but also _secure time and financial resources for faculty to remain engaged with research_. This typically means a reduced teaching load (often 3/2 or 2/2) with professional support funds.
{% endcapture %}
<div class="notice-gray">{{ criteria | markdownify }}</div>

If you are considering entering the job market, I'd encourage you to visit the [**Resources**](resources.html) pages for some insight into the ways in which PUIs might differ in their interviewing processes and values.

------------

# Who is hiring in CS so far (2022/23)


## 📋 Deadlines and Quick Links (_soonest on top_)
{: #deadlines}

💡 Deadlines are interpreted differently between institutions. See full description for context. 
{: .notice-blue}

{% capture table-style %}
{% include_relative deadlines.md %}
{% endcapture %}
<div class="styled-table"> {{ table-style | markdownify }} </div>


While I provide rough guidelines on teaching/scholarship balance, the schools here still cover a wide range of research resources and teaching loads. **Always ask questions**

------------

## 📣  Ads, Links, and Locations (_alphabetical order_) 

{% capture job-listing %}
{% include_relative descriptions.md %}
{% endcapture %}
<div class="jobs"> {{ job-listing | markdownify }} </div>
