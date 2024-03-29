Lists
=====

Creating Lists
~~~~~~~~~~~~~~
Users may create and save lists of features, such as gene IDs, transcript IDs, gene symbols, etc. The list tool searches the database for the list items and attempts to convert each identifier to the selected type. Click on the Lists tab from the menu to access the full list upload form. A short version of the form is also in the Quick List box on the home page.

.. figure:: images/lists-upload-form.jpg
   :alt: Lists Upload Form
   :figclass: align-center
   
   List upload form
   
..


.. figure:: images/lists-quick-list.jpg
   :width: 296
   :alt: Lists Quick List
   :figclass: align-center
   
   Quick list from AquaMine home page
   
..

As an example, enter the following comma-separated identifiers into the Lists upload form under the **Lists** tab.  Notice that they do not have to be in the same format.  A Summary table is displayed with the results of searching for each of the five identifiers in the list.

::

	LOC105319044, 114545253, wisp1, ENSONEG00000000134, gstk1
   


Leave the **Select Type** drop-down menu to **Gene** and the **Organism** drop-down to **Any**.  Click on **Create List**.  Note that you can also upload a list from a .txt file.

.. figure:: images/lists-results.jpg
   :alt: Lists results
   :figclass: align-center
   
   List Example: Search results for list of identifiers
   
..

The summary table provides information regarding those identifiers that had a direct hit without any duplicates.  If there are any duplicates, users can decide to add the relevant entries individually by clicking on the **Add** button under the **Action** column or choosing the **Add all** tab.  Here we will click **Add all**.  Once the selections have been added, the list can be saved by clicking the **Save a list of 31 Genes** button on the top of the summary table.  Name the list by entering text into the **Choose a name for the list** box at the top of the results page.


.. figure:: images/lists-results-save.jpg
   :alt: Lists save results
   :figclass: align-center
   
   List Example: Saving list of identifiers
   
..

After the list is saved, users are presented with a **List Analysis** page.  This page provides users with widgets to perform analyses on gene lists that they have created.

.. figure:: images/lists-analysis-page.jpg
   :alt: Lists analysis pate
   :figclass: align-center
   
   List Example: Analysis for gene list
   
..

The selection of widgets provided on the List Analysis page depend on the contents of the list. The available widgets for this list example include:

1. Gene Ontology Enrichment
2. Publication Enrichment
3. Pathway Enrichment

.. figure:: images/lists-widgets.jpg
   :width: 596
   :alt: Lists widgets
   :figclass: align-center
   
   List Example: Displayed widgets for list analysis
   
..

Before using the widgets, be sure to read the **Important Notes for Enrichment Widgets to avoid false positives**.


Saving Lists
~~~~~~~~~~~~
To see your saved lists, click the **View** tab on the **Lists** page. Note the saved list is highlighted in light purple and has a "MY" label in the corner. The remaining lists are gene lists for the organisms in AquaMine that can be used for future analyses. If not logged in, lists will be saved temporarily during your current session. However, you must be logged in to save your lists permanently.  Further analyses of lists can be done with the **Actions** links at the top of the list. The links become active once lists are selected for analyses.  Saved lists may also be accessed from the **MyMine** menu tab.

.. figure:: images/lists-saved.jpg
   :alt: Lists widgets
   :figclass: align-center
   
   List Example: Saved user lists

..

