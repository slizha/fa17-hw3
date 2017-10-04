## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
nil represents the value of an input element.

Go to `localhost:3000/teachers` in your browser; why does this not work?
It doesn't work because teacher hasn't been created yet and there is no route for get '/teachers'.

What type of request did your browser just perform?
A get request.

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
http://localhost:3000/teachers

Why does `localhost:3000/teachers` work now?
It works because it got there from a post request, which is in routes.
