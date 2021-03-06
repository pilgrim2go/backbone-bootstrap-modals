# BackboneBootstrapModals.BaseBodyView

`BaseBodyView` is the default implementation of a body view.

## Documentation Index

* [BaseBodyView's `options`](#basebodyviews-options)

## BaseBodyView's `options`

This view is specified with the following options.  These can be specified as properties when extending the class or passed in as options when instantiating this class.

| Property   | Description                                      | Default          |
| -----------|-------------------------------------------------:|-----------------:|
| text      | The text to in the modal body in within a `p` tag. An array of text can be specified for multiple tags. |                  |
| textTagName | The tag used for the body text elements         | `'p'`            |

**NOTE: While BaseHeaderView and BaseFooterView should be able to be leveraged as-is in many use cases -- it is expected that BaseBodyView would usually be replaced or extended by most applications.**

Example:

```javascript
view = new BackboneBootstrapModals.BaseBodyView({
  text: "hello world"
});

or

view = new BackboneBootstrapModals.BaseBodyView({
  text: ["line one", "line two"]
});
```
