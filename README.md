# Refine_RCS
A recipe for OpenRefine, that allows you to collect opensource informations on french companies based on their RCS (National Registry) number (9 digits), their SIRET (14 digits) or their VAT number.

Simply create a new project in Openrefine, copy/paste a list of company numbers in Openrefine in the clipboard zone.

Then apply the recipe.

IMPORTANT : 

This recipe uses the googlemap API to geocode the adresses. Replace "INSERT_YOUR_API_KEY_HERE" by your own API key in the recipe by your own key before applying it.

Threshold timer is set to 10000ms by default on googlemaps servers, to work with my configuration. 5000ms should work either.


OUTPUT : 

- Retrieve the name of the company, its adress, SIRET, APE code, Category, Capital stock, date of creation, owner, turnover (if available), year of birth of owner, status of the company (active, ceased), Type of company.
- geocode the adresses
- Check the validity of the VAT number on the VIES platform (E.U. public informations)
- Datestamp the search
- Retrieves avalable infos ont the company on VIES


VERSIONS :

2.0 : 14/08/2015. VAT identifier based on the Luhn Algorithm. Check and compare on the VIES platform

1.9 : 29/07/2015. Minor bugs fixed. added year of birth of owner, status of the company (active, ceased), Type of company

1.0 : 28/07/2015. INITIAL RELEASE




