# Paris JUG Website

## Creating Content

### Creating an Event

1. Create a document using:

```shell
hugo new content/events/<first_name>-<last_name>.md
```

2. Edit the event metadata:
* `date`: The date of the event (with time)
* `draft` (optional): If set to `true`, the event won't be published on website
* `publishDate` (optional): The date from which the event will be published (requires to rebuild the site)
* register (optional): The link to the eventbrite registration frame (ex `https://eventbrite.fr/tickets-external?eid=xxxx"`)
* `tags` (optional): A list of tags related to the event for navigation and SEO
* `title`: The title of the event (without date)
* `videos` (optional): A list of the replay videos (ex: `https://www.youtube.com/watch?v=xxxx`)

3. Add the event details as content

### Creating a Spearker

1. Create a document using:

```shell
hugo new content/speakers/<first_name>-<last_name>.md
```

2. Edit the speaker metadata: 

* `title`: The readable name of the speaker
* `twitter` (optional): The Twitter handle of the speaker (without `@`)

3. Add the speaker biography as content.

## Updating Sponsors

Sponsors data are located in three locations: 

1. `static/img/sponsors/` contains SVG image of the sponsors.  
Please make sure the logos does not contains margin.
You can easily trim them editing the `viewport` attribute of the image.
2. `layout/partials/widgets/sponsors.html` contains the HTML code of the sponsor sidebar widget.
3. `content/about/sponsors.md` contains the Markdown code of the sponsor Web page.
