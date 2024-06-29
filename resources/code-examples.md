## Two Column Layout

### Example
<img width="992" alt="Screenshot 2024-06-28 at 5 09 31 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/02645800-95a5-4aab-a128-8f3df7aff8e5">

## Instructions

Copy and paste the code above into the HTML editor of any section of your page where you would like to insert two columns. Replace the red italicized text, "Column 1 Content" and "Column 2 Content" with your own content. This code is mobile responsive, which means it will become two paragraphs in one column when viewed on a mobile device.


### Basic Code

```html
<div class="grid-row">
    <div class="col-xs-12 col-md-12 col-lg-6">
        <div style="flex: auto;">
            <p>Column 1 Content</p>
        </div>
    </div>
    <div class="col-xs-12 col-md-12 col-lg-6">
        <div style="flex: auto;">
            <p>Column 2 Content</p>
        </div>
    </div>
</div>
```
### Styling the Two Column Layout
## CSS Example
Below is an example of how to style the two-column layout using CSS to make it visually appealing.

```css
.grid-row {
    display: flex;
    flex-wrap: wrap;
    margin: 0 -15px;
}

.grid-row > [class*='col-'] {
    padding: 0 15px;
    margin-bottom: 30px;
}

.col-xs-12 {
    flex: 0 0 100%;
    max-width: 100%;
}

@media (min-width: 768px) {
    .col-md-12 {
        flex: 0 0 50%;
        max-width: 50%;
    }
}

@media (min-width: 992px) {
    .col-lg-6 {
        flex: 0 0 50%;
        max-width: 50%;
    }
}
```
