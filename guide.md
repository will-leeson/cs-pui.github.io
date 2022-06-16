---
layout: page
---

This website is manually updated. 

If you belong to a CS department (or just happen to catch a listing before I do), you can [**submit pull requests to add their own information.**](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

1. _Please make sure your department and university aligns with the criteria outlined on the [home page](index.html)_. I'd prefer to give everyone the benefit of the doubt and not act as a filter. 
2. Go to [the Github page that contains the job listings](https://github.com/cs-pui/cs-pui.github.io/blob/master/index.md)
3. Edit it following the template guidelines below and submit a pull request.

Feel free to email me at `evan.peck@bucknell.edu` if you run into any problems or need help with the process. I'm happy to add information for people who don't feel comfortable with the pull request process.

## Add info to _Deadlines and Quick Links_
Modify and paste the following template into [our listing page](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

```
- [College name](#your-college) - Deadline date, 2020
```

- **The closest deadlines should be on top**. In the event of multiple institutions choosing the same deadline, default to alphabetical order.

### Forthcoming info
If you would like to put a _placeholder_ in for an approved position in which you expect an ad soon, put it at the bottom of the list in the following format.

```
- [College name](#your-college) - _ad forthcoming_
```

## Add info to _Descriptions, Links, and Locations_
Modify and paste the following template into [our listing page](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

```markdown
### <a name="your-college"> [FT] Your College (Your State)</a>
_[Excerpt] This is where you add a paragraph from your job description_
- Insert a statement about your **deadline**
- [Link to application](https://enter-your-link.com)

_[back to deadlines](#deadlines)_
```

- Include your **state** next to your name (please only state). If outside the US, put country.
- Include either `[FT]` for fixed-term positions (where VAPs should go) or `[P]` for permanent positions (where tenure-track should go)
- Only include the most relevant paragraph. Your full job ad should be linked, so think of this as the teaser that gets applicants excited to read the rest.
- Make sure you are inserting this in the correct place alphabetically.
- `<a name="your-college">` below should match `(#your-college)` in the Deadlines section so that the internal link works.

### Forthcoming info
If you would like to put a _placeholder_ in for an approved position in which you expect an ad soon, continue to place it in alphabetical order with the following format.

```markdown
### <a name="your-college"> [P] Your College (Your State)</a>
_[Excerpt] Hiring is approved - ad is expected soon_

_[back to deadlines](#deadlines)_
```
