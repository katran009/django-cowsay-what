# Django-Cowsay-Generator
# Write a Django server that:#

# has a view for the index that does two things: if there is output, render it to the browser,#
# and always renders a fresh version of our form #
# has a form that just takes in a text line #
# has a model that we can save the text line to #
# on submission of the form, uses python's `subprocess` module to pass the submitted text to the cowsay #
# utility and retrieves the output #
# re-renders the homepage with a fresh form and the output from cowsay #
# backs up a copy of the text the user submitted #
# has a page at the endpoint /history that displays the 10 most recent strings submitted #
