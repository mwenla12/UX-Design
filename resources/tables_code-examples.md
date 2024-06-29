# Basic Tables

## Example

<img width="965" alt="Screenshot 2024-06-28 at 5 50 53 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/86bb6548-7e3d-4df2-8ab6-469de977becd">


### Basic Code

```html
<table class="ic-Table ic-Table--hover-row border border-trbl" style="background-color: white;">
    <caption>*Insert Table Caption*</caption>
    <thead>
        <tr>
            <th scope="col">*Insert header, row 1 cell 1*</th>
            <th scope="col">*Insert header, row 1 cell 2*</th>
            <th scope="col">*Insert header, row 1 cell 3*</th>
            <th scope="col">*Insert header, row 1 cell 4*</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>*Insert data, row 2 cell 1*</td>
            <td>*Insert data, row 2 cell 2*</td>
            <td>*Insert data, row 2 cell 3*</td>
            <td>*Insert data, row 2 cell 4*</td>
        </tr>
        <tr>
            <td>*Insert data, row 3 cell 1*</td>
            <td>*Insert data, row 3 cell 2*</td>
            <td>*Insert data, row 3 cell 3*</td>
            <td>*Insert data, row 3 cell 4*</td>
        </tr>
    </tbody>
</table>
```
### Instructions
Copy and paste the code above into the HTML editor of any section of your page where you would like to insert a table. Replace the red, italicized "Insert Table Caption" text with a short header or description of what this table is about. Replace the red, italicized "Insert header, row 1 cell 1...cell 4" text with the header text you want in each column. Replace the red, italicized "Insert data, row 2 cell 1...cell 4" text with the corresponding data you want in the row below the header row. Replace the red, italicized "Insert data, row 3 cell 1...cell 4" text with the corresponding data you want in the following row.


### Styling the Table
CSS Example

Below is an example of how you can style the table to add striped rows for better readability.

```css
.striped-table {
    width: 100%;
    border-collapse: collapse;
}

.striped-table th, .striped-table td {
    padding: 12px;
    text-align: left;
    border: 1px solid #ddd;
}

.striped-table tr:nth-child(even) {
    background-color: #f2f2f2;
}

.striped-table th {
    background-color: #4CAF50;
    color: white;
}
```
