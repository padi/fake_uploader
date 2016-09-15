# Fake Uploader

First working example of a web app using Elixir's Plug.
See: https://elixirschool.com/lessons/specifics/plug/#creating-a-plug

# Specifications
* Welcomes the user on root ("/") by printing "Welcome"
* Any POST /upload request...
  * ... with "content" and "mimetype" should print "Uploaded".
  * Otherwise, return an empty 500 error.
* Doesn't welcome the user on other routes by priting "Oops"
