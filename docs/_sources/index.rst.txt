Deep mutational scanning of SARS-CoV-2 Omicron BA.1 spike and mapping of escape mutations for COV2-2130 and its derivative antibody
===================================================================================================================================

This page documents the data analysis.
For the actual code, see https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130

Study by Bernadeta Dadonaite and Jesse Bloom.

Workflow
--------
Below is the rulegraph for the `snakemake <https://snakemake.readthedocs.io/>`_ workflow.
Click :download:`here <../../results/docs_source/filegraph.svg>` for the more detailed filegraph.

.. image:: ../../results/docs_source/rulegraph.svg
   :width: 800

Analysis notebooks
------------------
Many of the plots in these notebooks are interactive, so try mousing over points for
details, using dropdowns, etc.

.. toctree::
   :maxdepth: 1

   analyze_variant_counts
   analyze_prob_escape
   fit_polyclonal
   avg_antibody_escape
   compare_IC50s

Data files
----------
- `parental gene sequence <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/gene_sequence/codon.fasta>`_
- `parental protein sequence <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/gene_sequence/protein.fasta>`_
- `sequential-to-reference site numbers <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/site_numbering/site_numbering_map.csv>`_
- `codon-variant table <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/variants/codon_variants.csv>`_
- `processed barcode sequencing runs <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/barcode_runs/processed_barcode_runs.csv>`_
- `variant counts <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/variant_counts>`_
- `antibody selection experiments <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/prob_escape/antibody_selections.csv>`_
- `antibody escape values <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/antibody_escape>`_
- `sequential to reference site numbering <https://github.com/dms-vep/SARS-CoV-2_Omicron_BA.1_spike_DMS_COV2-2130/blob/main/./results/site_numbering/site_numbering_map.csv>`_

Interactive plots of mutation antibody escape
---------------------------------------------
- `2130-1-0114-112 escape plot <2130-1-0114-112_escape_plot.html>`_
- `COV2-2130 escape plot <COV2-2130_escape_plot.html>`_

