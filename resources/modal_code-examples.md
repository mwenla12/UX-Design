# Basic Modals

## Example

<img width="117" alt="Screenshot 2024-06-28 at 6 40 49 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/9b6e17e4-8f55-40dc-a30f-f810610db353">

<img width="1382" alt="Screenshot 2024-06-28 at 6 41 01 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/e8e11e1e-afbc-4b19-9407-2a7f6dc2a9d3">


### Basic Code

```html
<!-- Trigger/Open The Modal -->
<button id="myBtn">Open Modal</button>

<!-- The Modal -->
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <p>Some text in the Modal..</p>
  </div>
</div>
```
## Styling the Modal

###CSS Example
####Below is an example of how you can style the modal to make it visually appealing.

```
/* The Modal (background) */
.modal {
    display: none;
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0,0.4);
    padding-top: 60px;
}

/* Modal Content */
.modal-content {
    background-color: #fefefe;
    margin: 5% auto;
    padding: 20px;
    border: 1px solid #888;
    width: 80%;
}

/* The Close Button */
.close {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
}

.close:hover,
.close:focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
}
```
## Instructions

Copy and paste the HTML code above into the HTML editor of any section of your page where you would like to add a modal. Copy and paste the CSS into your stylesheet to style the modal.
