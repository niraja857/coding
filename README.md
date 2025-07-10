code explanation:-
Takes a search query from the user (e.g., "cancer immunotherapy").

Fetches matching paper PubMed IDs using the Entrez API.

Downloads the MEDLINE records for those papers.

Filters papers where at least one author is affiliated with a pharma or biotech company.

Saves the filtered papers to a CSV file.

