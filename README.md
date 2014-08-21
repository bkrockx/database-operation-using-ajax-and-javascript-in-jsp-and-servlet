database-operation-using-ajax-and-javascript-in-jsp-and-servlet
===============================================================

flow of code:->

Display3.java -> home1.jsp ->(if delete button clicked) -> deleteData1.java -> Display3.java (cycle)

                 home1.jsp ->(if edit button clicked) -> show corresponding row contents in textboxes
                 
                 home1.jsp ->(if show button clicked) -> Display4.java -> home2.jsp
                 
                 home1.jsp ->(if save button clicked) -> UpdateData1.java -> Display4.java -> home2.jsp
