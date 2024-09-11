# html_spa_changes

Written as a solution to an issue that can arise with SPAs and Optimizely Web. This was designed to address an issue where the Optimizely Visual Editor was not persisting changes made to an SPA site. I've created an Optimizely Extension that implements a robust mutation observer to ensure the changes stick. 

**Steps to Implement**

Locate the json_config.json file provided in this repo.
Copy the JSON file.
Visit Implementation -> Extensions (Tab) --> Create New Extension --> Using JSON
Paste the JSON in the field and save
In the Extensions menu, click the Three Dots associated with HTML Changes for SPAs, and click Enable.
The Extension is now available in the Visual Editor panel for each experiment.

To Apply to An Experiment

Visit the experiment in question
Select Create
Select HTML Changes for SPAs
Insert the selector of the HTML you'd like to alter
Make the necessary adjustments
Save your changes
