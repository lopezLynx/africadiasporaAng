# Defines all Languages known to GitHub.
#
# type              - Either data, programming, markup, prose, or nil
# aliases           - An Array of additional aliases (implicitly
#                     includes name.downcase)
# ace_mode          - A String name of the Ace Mode used for highlighting whenever
#                     a file is edited. This must match one of the filenames in http://git.io/3XO_Cg.
#                     Use "text" if a mode does not exist.
# wrap              - Boolean wrap to enable line wrapping (default: false)
# extensions        - An Array of associated extensions (the first one is
#                     considered the primary extension)
# interpreters      - An Array of associated interpreters
# searchable        - Boolean flag to enable searching (defaults to true)
# search_term       - Deprecated: Some languages maybe indexed under a
#                     different alias. Avoid defining new exceptions.
# color             - CSS hex color to represent the language.
# tm_scope          - The TextMate scope that represents this programming
#                     language. This should match one of the scopes listed in
#                     the grammars.yml file. Use "none" if there is no grammar
#                     for this language.
# group             - Name of the parent language. Languages in a group are counted
#                     in the statistics as the parent language.
#
# Any additions or modifications (even trivial) should have corresponding
# test change in `test/test_blob.rb`.
#
#### Please keep this list alphabetized. Capitalization comes before lower case.
*Olanrewaju* is just testing __GFM__.
These are the types of flowers that i know:
- Hibiscus
- Roses
- Dafodils
* Pride of Barbados
