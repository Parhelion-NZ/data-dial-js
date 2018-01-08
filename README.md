# data-dial-js
Trusted Data dial widget for embedding in HTML

## Transparent Data Use Wheel script.
### Developed for the [Data Futures Partnership](http://datafutures.co.nz) by [Parhelion](http://www.parhelion.co.nz)

To use on your website, first visit the [Transparent Data Website](http://trusteddata.co.nz), and complete the eight questions.

Next include a link to this script with your other scripts, generally in your page <head> section, or at the bottom of the page:

```html
<script src="http://trusteddata.co.nz/media/dataFutures.js" async defer></script>
```

Next, in your page, insert the code below.  Your answers will be pulled in and displayed in the wheel.

```html
<div id="dataFutures" data-wheel-id="[your code]"></div>
```

### Styling:
The wheel itself is sized at 350x350px.  Your answers will be injected into a named div inside the div you inserted above, with the id 'dataFuturesGuidelinesAnswers'.

The script will inject standard styling for these elements.  To suppress this and use your own CSS, append ```data-style="none"``` to the #dataFutures div above.  The hierarchy of injected content is shown below.

```html
<div id="dataFutures">
  <canvas id="dataFuturesWheelCanvas"/>
  <div id="dataFuturesGuidelinesAnswers">
    <div id="dataFuturesGuidelinesAnswersQuestion">
      <h1 class="dataFuturesQuestion">
        [question injected here]
      </h1>
      <div id="dataFuturesGuidelinesAnswersAnswer">
        [answer injected here]
      </div>
   </div>
</div>
```
### Embedding in other CMS systems
We have also created modules for some popular Content Management Systems, to make embedding the dial easier for users without needing to edit code.  Links to come... 

### Further information
You can see a library of dials created by other businesses at https://trusteddata.co.nz/dial-library

Please log bugs to https://github.com/Parhelion-NZ/data-dial-js

For further assistance contact colin@parhelion.co.nz

### Licence
MIT Licence
