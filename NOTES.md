# References
 - Use Calysto:
   * document-tools
   * provides make references
   * references are created using [CITE](#cite-<bibtex_cite_key)
   * creates #References cell at bottom of notebook
   * installation: https://github.com/Calysto/notebook-extensions
   * Drawbacks: 
     bibtex entries have to be inside the notebook, no external bibtex allowed
     no search functionality for bibtex entries
     have to install whole calysto project (users & when running notebook)

 - Make subtype of calysto:
   * Can make references from external file
   * make light-weight install available for document tools
   * include search for references
   * include nbconvert latex reference for pdf creation

This allows to create pdf in travis

# Testing

How to run notebooks on travis?
Idea:
 1. Install requirements
 2. Run notebook all the way through
 3. push comment on pull request, showing failure, if it happens
 4. push comment on pull request, showing success (maybe ok just with travis api)

# Comments & Corrections

Put comments directly into notebook? 
 1. Have commenting/suggestion mode on notebook
    This would be a commit by the reviwers, changing the notebook.
    Would require the user to download the branch again.
 2. Comment like done in https://github.com/MC-Notes/Issue1/pull/1
    This allows for corrections to be done directly by the next commit.

