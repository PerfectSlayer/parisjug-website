# Paris JUG Website

## New Dev

1. Fork and clone locally this repository

2. In the root folder:

```shell
git submodule update --init
```

3. Test locally:

```shell
hugo server -D
```

## Creating Content

### Creating an Event

1. Create a document using:

```shell
hugo new content/events/<year>/<month>-<day>-<name>.md
```

2. Edit the event metadata:

- `date`: The date of the event (with time)
- `draft` (optional): If set to `true`, the event won't be published on website
- `publishDate` (optional): The date from which the event will be published (requires to rebuild the site)
- register (optional): The link to the eventbrite registration frame (ex `https://eventbrite.fr/tickets-external?eid=xxxx"`)
- `tags` (optional): A list of tags related to the event for navigation and SEO
- `title`: The title of the event (without date)
- `videos` (optional): A list of the replay videos (ex: `https://www.youtube.com/watch?v=xxxx`)

3. Add the event details as content

### Creating a Spearker

1. Create a document using:

```shell
hugo new content/speakers/<first_name>-<last_name>.md
```

2. Edit the speaker metadata:

- `title`: The readable name of the speaker
- `twitter` (optional): The Twitter handle of the speaker (without `@`)

3. Add the speaker biography as content.

### Updating Sponsors

Sponsors data are located in three locations:

1. `static/img/sponsors/` contains SVG image of the sponsors.  
   Please make sure the logos does not contains margin.
   You can easily trim them editing the `viewport` attribute of the image.
2. `layout/partials/widgets/sponsors.html` contains the HTML code of the sponsor sidebar widget.
3. `content/about/sponsors.md` contains the Markdown code of the sponsor Web page.

## Web site custom features

### Content Automation

- The home page contains the last events and shows:
  - The registration link a week before the start of the event,
  - The event video if present and event is past,
  - The event details summary if details section is present,
  - The event summary otherwise.
- Speakers page in an automatec alphabetic index.
- Speaker conference list from the speaker page is updated if a speaker is mentioned in an event content.
- Speaker profile picture comes from the Twitter and is regularly updated.

### Custom Shortcodes

There is two kinds of custom short codes: generic ones, and section ones.
The section shortcode are expected to be used within `event` page content.

### Code of Conduct Section

The `coc-section` shortcode renders a page section with our code of conduct:

`{{% coc-section %}}`

### Replay Section

The `replay-section` shortcode renders a page section with YouTube thumbnails and links of an event videos:

`{{< replay-section >}}`

### Sponsor Section

The `sponsor-section` shortcode renders a page section with the year-related sponsors of the event:

`{{< sponsor-section >}}`

### Iframe

The `iframe` shortcode allows to insert safe frame into pages:

`{{< iframe src="https://example.com" title="content-title" width="425" height="350" >}}`

Using the following parameters:

- `src`: The target of the frame,
- `title` _recommanded_: The description of the frame content for accessibility,
- `width` _optional_: The width of the frame (in pixel),
- `height` _optional_: The height of the frame (in pixel).

### Gallery

The `gallery` shortcode generates an image gallery from page resources:

`{{< gallery match="images/*" >}}`

Using the following paramters:

- `match` _optional_: The path of images to include to the gallery (`gallery/*`) by default.

### Flickr slideshow

The `flickr` shortcode generates a gallery from a Flickr album:

`{{< flickr id="72157659120711844" img="https://live.staticflickr.com/5783/23153505766_8b0cb95615_z.jpg" >}}`

Using the following paramters:

- `id`: the Flickr album id
- `img`: the static URL of a picture in the album

## Third Parties

- [Mainroad](https://github.com/Vimux/Mainroad) (GLP 2.0)
- [medium-zoom](https://github.com/francoischalifour/medium-zoom) (MIT)
