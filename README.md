# Refine_RCS
A recipe for OpenRefine, that allow you to collect opensource informations from french companies based on their RCS (National Registry) number.

Simply create a new project in Openrefine, copy/paste a list of RCS numbers in Openrefine in the clipboard zone.

Then apply the recipe.

IMPORTANT : 

This recipe uses the googlemap API to geocode the adresses. Replace "INSERT_YOUR_API_KEY_HERE" by your own API key in the recipe by your own key before applying it.

Threshold timer is set to 10000ms by default on googlemaps servers, to work with my configuration. 5000ms should work either.


OUTPUT : 

- Retrieve the name of the company, its adress, SIRET, APE code, Categoty, Capital stock, date of creation, owner, turnover (if available), year of birth of owner, status of the company (active, ceased), Type of company.
- geocode the adress


VERSIONS :

1.0 : INITIAL REALEASE

1.9 : 29/07/2015. Minor bugs fixed. added year of birth of owner, status of the company (active, ceased), Type of company


