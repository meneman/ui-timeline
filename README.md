# ui-timeline

  ui-timeline is a way to display your items similar to bullet items, the
  difference is that items are listed at the center with a left and right content.

## Usage

  1. Import the component.
  `<link rel="import" href="ui-timeline/ui-timeline.html">`

  2. Html Usage.
  `<ui-timeline
    items='[{
      "left":
        { "type": "header", "content": "Label 1" },
      "center":
        { "dotColor": "dark" },
      "right":
        { "type": "text", "content": "I am a sample content 1." }
      },
      {
      "left":
        { "type": "text", "content": "I am a sample content 2." },
      "center":
        { "dotColor": "light" },
      "right":
        { "type": "header", "content": "Label 2" }
      },
      {
      "left":
        { "type": "header", "content": "Label 3" },
      "center":
        { "dotColor": "dark" },
      "right":
        { "type": "text", "content": "I am a sample content 3." }
      },
      {
      "left":
        { "type": "text", "content": "I am a sample content 4." },
      "center":
        { "dotColor": "light" },
      "right":
        { "type": "header", "content": "Label 4" }
      }]'
    label="ui-timeline">
  </ui-timeline>`


## For detailed usage

  Please refer to the demo page under demo directory.