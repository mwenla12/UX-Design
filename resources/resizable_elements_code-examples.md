# Basic Resizable Elements

## Example

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce dignissim scelerisque ornare. Nullam suscipit lectus vitae nulla fringilla dapibus. Praesent ultricies interdum finibus. Aliquam quis velit sed nisi porta ullamcorper id eget neque. Fusce malesuada fermentum vulputate. Pellentesque ut suscipit nibh, eget facilisis sem. Mauris a est a velit rhoncus imperdiet quis scelerisque ante. Morbi lacinia justo sed lacinia eleifend. Suspendisse et eros et quam faucibus tincidunt.

### Basic Code

```html
<div style="width: 100%; height: 400px;">
    <div class="enhanceable_content resizable" style="text-align: center; background-color: #68838b; color: #ffffff; width: 400px; height: 50px;">
        <p style="padding: 15px;">Click the corner to make this box bigger or smaller</p>
    </div>
</div>
```

### Styling the Resizable Elements
#### CSS Example

Below is an example of how you can style the resizable elements to make them visually appealing.

```css
.resizable {
    resize: both;
    overflow: auto;
    border: 2px solid #ccc;
    padding: 10px;
    box-sizing: border-box;
    max-width: 100%;
    max-height: 100%;
}
```
### Instructions
#### Copy and paste the HTML code above into the HTML editor of any section of your page where you would like to add resizable elements. Copy and paste the CSS into your stylesheet to apply the styling to your resizable elements. Adjust the styling as needed to fit your design.
