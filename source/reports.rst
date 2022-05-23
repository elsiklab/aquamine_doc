Report Pages
============

All objects in AquaMine (e.g., gene, protein, transcript, publication) have report pages that can viewed after running a query.  It allows users to view all available information for that object while providing links to related objects.  As an example, we can revisit the templates example.  In the list of templates under the **Templates** tab on the AquaMine home page, select Gene -> Protein Sequences to query AquaMine to retrieve all protein sequencess for a given gene. Enter the Gene ID "ENSELUG00000001587" into the the LOOKUP search box then click **Show Results**.  In the results table, note that every entry is contains a link.  You can mouse over any link to bring up a summary of that object. If we hover over the first Gene ID, we can see a summary box that includes information about that particular gene.

.. figure:: images/reports-summary.png
   :width: 380
   :alt: Report summary box
   :figclass: align-center
   
   Summary for gene entry in query results table
   
   ..

Clicking on that same link will bring up its report page that includes a comprehensive overview for that gene.  The report page header shows the Gene ID and its Biotype, for this example, protein coding. The tabs at the top of the page in the Quick Links menu bar quickly bring you to the data listed. The column on the right side of the report page displays external links to other Mines and databases.

.. figure:: images/reports-page.png
   :width: 696
   :alt: Report page
   :figclass: align-center
   
   Report page for protein-coding gene
   
   ..

The content of the report page is divided into categories based on the type of information provided for that particular object. Clicking on links within each category bring up more details about the objects of interest.

Summary
~~~~~~~
The **Summary** section near the top of the report provides information on the gene such as its length, chromosome location, and strand information.  Users can also get the complete FASTA sequence of the gene by clicking on the FASTA tab.

.. figure:: images/reports-page-summary.png
   :width: 696
   :alt: Report page summary section
   :figclass: align-center
   

Transcripts
~~~~~~~~~~~
The **Transcripts** section contains information about the gene model, such as transcripts and exons. Links to FASTA files are included where applicable.

.. figure:: images/reports-page-transcripts.png
   :width: 696
   :alt: Report page transcript section
   :figclass: align-center
   

Proteins
~~~~~~~~
The **Proteins** section provides information about the protein product of the gene. The comments section gives a brief description about the protein along with the UniProt accession and links to any outside data sets.

.. figure:: images/reports-page-proteins.png
   :width: 696
   :alt: Report page protein section
   :figclass: align-center
   


Function
~~~~~~~~

The **Function** section displays Gene Ontology annotations for a gene. Annotations are divided into three categories:

* Cellular Component
* Molecular Function
* Biological Process


The GO terms are displayed along with the evidence code indicating how the annotations were derived.  A results with Pathway information is also displayed if applicable.

.. figure:: images/reports-page-function.png
   :width: 696
   :alt: Report page function section
   :figclass: align-center
   


Homology
~~~~~~~~

The **Homology** section provides information for all homologues and displays a summarized view of the homologues reported in different organisms.

.. figure:: images/reports-page-homology.png
   :width: 696
   :alt: Report page homology section
   :figclass: align-center
   

Publications
~~~~~~~~~~~~
The **Publications** section displays a table of publications related to the gene with links to full citations.

.. figure:: images/reports-page-publications.png
   :width: 696
   :alt: Report page publication section
   :figclass: align-center
   


Other
~~~~~
This last section provides miscellaneous information that do not fit into any of the above categories.  This example lists other data sets that the gene belongs to.

.. figure:: images/reports-page-other.png
   :width: 696
   :alt: Report page other section
   :figclass: align-center

