# MetaboliteTransitive
# Language: Python
# Input: TXT
# Output: CSV
# Tested with: PluMA 1.1, Python 3.6
# Dependency: scipy==1.4.1

PluMA plugin that builds taxa-to-metabolite connections, using
transitivity through genes

The plugin takes as input a tab-delimited file of keyword-value pairs:

HMDB2KEGG: Mapping, HMDB identifiers to KEGG
taxaToGenes: Mapping, taxa to genes
genesToReactions: Mapping, genes to reactions

Output file is a CSV file of mapping from taxa to metabolites
