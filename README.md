# ui-timeline
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Componetized/ui-timeline)

  ui-timeline is a way to display your items similar to bullet items, the
  difference is that items are listed at the center with a left and right content.

## Usage

```html
<link rel="import" href="ui-timeline/ui-timeline.html">
```

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="ui-timeline.html">
    <dom-bind>
      <ui-timeline
        id='uiTimeline'
        label="ui-timeline"
        items="[[data]]">
      </ui-timeline>
    </dom-bind>
    <script>
      var autobind = document.querySelector('dom-bind');

      autobind.data = [{
        left:
          { type: "header", content: "Label 1" },
        center:
          { dotColor: "dark" },
        right:
          { type: "text", content: "I am a sample content 1." }
        },
        {
        left:
          { type: "text", content: "I am a sample content 2." },
        center:
          { dotColor: "light" },
        right:
          { type: "header", content: "Label 2" }
        },
        {
        left:
          { type: "header", content: "Label 3" },
        center:
          { dotColor: "dark" },
        right:
          { type: "text", content: "I am a sample content 3." }
        },
        {
        left:
          { type: "text", content: "I am a sample content 4." },
        center:
          { dotColor: "light" },
        right:
          { type: "header", content: "Label 4" }
        }];
    </script>
  </template>
</custom-element-demo>
```
-->
```html
<dom-bind>
  <ui-timeline
    id='uiTimeline'
    label="ui-timeline"
    items="[[data]]">
  </ui-timeline>
</dom-bind>
<script>
  var autobind = document.querySelector('dom-bind');

  autobind.data = [{
    left:
      { type: "header", content: "Label 1" },
    center:
      { dotColor: "dark" },
    right:
      { type: "text", content: "I am a sample content 1." }
    },
    {
    left:
      { type: "text", content: "I am a sample content 2." },
    center:
      { dotColor: "light" },
    right:
      { type: "header", content: "Label 2" }
    },
    {
    left:
      { type: "header", content: "Label 3" },
    center:
      { dotColor: "dark" },
    right:
      { type: "text", content: "I am a sample content 3." }
    },
    {
    left:
      { type: "text", content: "I am a sample content 4." },
    center:
      { dotColor: "light" },
    right:
      { type: "header", content: "Label 4" }
    }];
</script>
```
