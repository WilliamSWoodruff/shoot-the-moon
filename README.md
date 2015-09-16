moon-me
=================
Material Design date picker, compatible with *Polymer 1.0*

Provides a responsive date picker based on the material design spec. This
component aims to be a clone of the date picker introduced in Android Lollipop.

![wide picker screenshot][wide] ![narrow picker screenshot][narrow]

See the [component page](http://bendavis78.github.io/moon-me/) for 
full documentation.

## Example usage:

Default picker:

```html
<moon-me></moon-me>
```

Setting the initial date to April 20, 2015:

```html
<moon-me date="2014-04-20"></moon-me>
```

If you include this element as part of `paper-dialog`, use the class
`"moon-me-dialog"` on the dialog in order to give it proper styling.

```html
    <paper-action-dialog id="dialog" modal class="moon-me-dialog">
      <moon-me id="datePicker"></moon-me>
      <div class="buttons">
        <paper-button dialog-dismiss>Cancel</paper-button>
        <paper-button dialog-confirm>OK</paper-button>
      </div>
    </paper-action-dialog>
```

---

If you find this component useful, please show your support by donating to
[Bold Idea](http://boldidea.org). Click the button below!

[![ideaSpark campaign button][donate]](https://donorbox.org/bold-idea-make-ideaspark-possible-for-dallas-area-students)

[wide]: http://i.imgur.com/pnKuwtk.png
[narrow]: http://i.imgur.com/ExhVflG.png
[donate]: http://www.boldidea.org/donate-badge-md-1.png
