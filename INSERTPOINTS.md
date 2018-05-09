## Usage

### Include: Page

``` hbs
{{! @INSERT :: START @id: youtube-video, @tag: component-partial }}
{{#with youtube-video.variations.default}}
    {{> youtube-video settings=this.settings content=this.content}}
{{/with}}
{{! @INSERT :: END }}
```
