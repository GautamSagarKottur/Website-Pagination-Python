# Website-Pagination-Python

Given a list of items with a relevance score and price of that item, this notebook assigns page numbers sorts the items(asc/desc) based on either the relevance or the price, no.of items in any given page and the actual items in that page.


Product list = list of lists with "name-of-the-item", relevance-score, price

Create a function:

to sort, the product list using column passed as an argument

assign page numbers to each product based in itemsPerPage number passed as an argument

get names of the items which are there on a pagenumber passed as an argument


Arguments:

df: that was created from the list of lists

n: column number that is used to sort the df

sort: sort ascending or descending (0 or 1)

itemsperPage: no.of items that you want to have in each page

number_of_the_page: number of the page from which you want to see the elements in that page.
