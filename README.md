ServiceDataFormatLibrary
========================

The idea behind this project is to create a set of JSON files that 
mimic typical result sets from popular services. To be clear, this
project isn't about *enabling* mocking in your client. There are
plenty of solutions out there that support that. Rather, this library
gives you the *form* of popular service APIs so your code can more accurately
work with mock data.

Directory
=========

Each service has a folder along with a number of json files. Each file is 
named according to what it represents, so for example, there is a  search_for_starwars.json
file in the Twitter folder. This is a result set from performing a Twitter
search. (Duh.)

Updates
=======

v0: Initial release.