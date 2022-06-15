---
layout: page
---
<link rel="stylesheet" href="cspui.css">

### Adding your position to CS-PUI

While I often try to post positions quickly after they go live, 

If you belong to a CS department (or just happen to catch a listing before I do), you can [**submit pull requests to add your own information.**](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)


**Steps:** the positions on this page should be...
1. _Make sure your department and university aligns with the criteria_. I'd prefer to give everyone the benefit of the doubt and not act as a filter. [see the criteria](index#criteria)
2. Edit [`deadlines.md`](https://github.com/cs-pui/cs-pui.github.io/blob/master/_includes/deadlines.md) with your application deadline [see more instructions](faq#scope)
3. Edit [`descriptions.md`](https://github.com/cs-pui/cs-pui.github.io/blob/master/_includes/descriptions.md) with an excerpt from your ad, location, link, and deadline. 

Feel free to email me at `evan.peck@bucknell.edu` if you run into any problems or need help with the process. I'm happy to add information for people who don't feel comfortable with the pull request process.

----------------

### ✅ Add your Deadline

1. [Edit the `deadlines.md` files linked here](https://github.com/cs-pui/cs-pui.github.io/blob/master/_includes/deadlines.md) by clicking the `Edit this file` button (a small pencil)
2. 

----------------

### ✅ Adding your Description 

[Access the `descriptions.md` files linked here](https://github.com/cs-pui/cs-pui.github.io/blob/master/_includes/descriptions.md)

Given the following template, modify it with your advertisement's information (see [worked example below](#desc-example)), and then copy-paste it into [`descriptions.md`](https://github.com/cs-pui/cs-pui.github.io/blob/master/_includes/descriptions.md), making sure that it is in correct alphabetical order with respect to other institutions. 
```
### University Name
{: #university-anchor}

[Excerpt] This is where you add a paragraph from your job ad. 

- 1st bullet should be about your app deadline. **date in bold**
- 2nd bullet should include your location

[Full Job Ad](https://this-should-be-the-link-to-your-ad.edu){: .button-ad} 
[_back to all deadlines_](#deadlines)

------------
```

{% capture formatting %}
💡 **The spacing and ordering is important for a correct CSS interpretation**. For example:
-  the `**` bold markers in the 1st bullet point will style your date with a blue box. 
- Keeping no line spacing between the `Full Job Ad` and `_back to all deadlines_` will ensure the buttons are next to each other
{% endcapture %}
<div class="notice-blue">{{ formatting | markdownify }}</div>


#### _Example: Ipsum University_
{: #desc-example}

An example of modifying the template above to include information about a fictional _Ipsum University_


![continuum of teaching and research](img/modify-template.png)


If done correctly, the text above should be automatically formatted and translatted as the following on the cs-pui website...


![continuum of teaching and research](img/output.png)