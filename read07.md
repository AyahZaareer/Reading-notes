# Tables
### A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

## Basic Table Structure: 

**< table>**

The <table> element is used
to create a table. The contents
of the table are written out row
by row.
  
 **< tr>**
 
You indicate the start of each
row using the opening <tr> tag.
(The tr stands for table row.)
It is followed by one or more
<td> elements (one for each cell
in that row).
At the end of the row you use a
closing </tr> tag.

**< td>**

Each cell of a table is
represented using a <td>
element. (The td stands for
table data.)
At the end of each cell you use a
closing </td> tag.

![image](https://user-images.githubusercontent.com/79833733/111921214-0185a880-8a9c-11eb-84f9-ad0d7c06c02c.png)

## Table Headings:
**< th>**

The <th> element is used just
like the <td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.
  
##  Spanning ColumnS:
### Sometimes you may need the entries in a table to stretch across more than one column. The colspan attribute can be used on a < th> or < td> element and indicates how many columns that cell should run across.


![image](https://user-images.githubusercontent.com/79833733/111921306-925c8400-8a9c-11eb-81d1-babda675285b.png)


## Spanning Rows:
### You may also need entries in a table to stretch down across more than one row. The rowspan attribute can be used on a < th> or < td> element to indicate how many rows a cell should span down the table.

![image](https://user-images.githubusercontent.com/79833733/111921360-d0f23e80-8a9c-11eb-8d12-3679eff8ca06.png)

## Long Tables:
### There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table .

**< thead>** The headings of the table should sit inside the <thead> element.

**< tbody>** The body should sit inside the  < tbody> element.

**< tfoot>** The footer belongs inside the < tfoot> element.

![image](https://user-images.githubusercontent.com/79833733/111921465-6ab9eb80-8a9d-11eb-80db-8fa0f5bc130f.png)     ![image](https://user-images.githubusercontent.com/79833733/111921478-7c02f800-8a9d-11eb-9507-1889b0ada56a.png)



## Old Code: Width & Spacing

![image](https://user-images.githubusercontent.com/79833733/111921522-b8ceef00-8a9d-11eb-9077-15cb072dc3b0.png)     ![image](https://user-images.githubusercontent.com/79833733/111921536-c8e6ce80-8a9d-11eb-80f5-ca032c2b1d8a.png)



## Old Code: Border & Background

![image](https://user-images.githubusercontent.com/79833733/111921567-ee73d800-8a9d-11eb-8974-d040518b8992.png)       ![image](https://user-images.githubusercontent.com/79833733/111921585-00557b00-8a9e-11eb-8978-d92f62ac083d.png)




