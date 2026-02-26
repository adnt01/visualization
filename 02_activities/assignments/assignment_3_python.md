# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    Visualization1- Python Matplotlib:
    > What software did you use to create your data visualization?

        I used Python library matplotlib.

    > Who is your intended audience?

        My intended audience is the medical staff (doctors, nurses, any heath personnel)
    
    > What information or message are you trying to convey with your visualization?
    
        I am trying to convey the total number of Causative Agent-1 for the year 2025 in Toronto healthcare institutions (hospitals, long-term care homes and retirement homes).
        Causative Agent-1 is the first identified factor (or pathogen) that caused the condition or disease under study.
        Causative Agent-1 is composed of 23 viruses listed below:
            Influenza A (H3)', 'Influenza A (Not subtyped)', 'Unable to identify', 'Parainfluenza', 'Enterovirus/ Rhinovirus',
            'COVID-19', 'Coronavirus*', 'Rhinovirus', 'Influenza A (H1)', 'Influenza A (H3N2)', 'Respiratory syncytial virus',
            'Influenza A (H1N1)', 'Norovirus', 'Metapneumovirus', 'CPE Colonization Enterobacter cloacae (VIM)',
            'Clostridium difficile', 'CPE Colonization Klebsiella pneumoniae (KPC)', 'Enterovirus',
            'CPE Colonization Klebsiella oxytoca (NDM)', 'Rotavirus', 'Influenza A ((H1N1)pdm09)',
            'CPE Colonization Citrobacter freundii (KPC)', 'Parainfluenza type 3'

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?

        I considered the following in the design:
        Aesthetic: I choose bar plot with blue color that is nice to look at. 
        Substantive: The bar plot represent the total number of respiratory cases caused by the viruses listed in Causative Agent-1.
        Perception: Bar plot showing the different viruses in year 2025, The bars are colored in blue, except for Covid-19 bar since it has the highest count (256 cases).
   
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

        I used Python library matplotlib to ensure my data visualizations are reproducible.
        If I used a tool that make your data visualization is not reproducible, my visualization might not be trusted enough if some one else was not able to reach the same result.
    
    > How did you ensure that your data visualization is accessible?

        To ensure my data visualization is accessible, I utilized title, X-axis, and Y-axis labels .
    
    > Who are the individuals and communities who might be impacted by your visualization?  

        Patients, doctors, nurses, persons working in Toronto healthcare institutions since my visualizations might help Toronto healthcare institutions to have appropriate stock of medication for each type of virus.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?

        I chose the features that have lot of values, for example Causative Agent-1 has no missing values (979 non-null), I did not use Causative Agent-2 because it is populated in 14 records only (14 non-null).
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    
        To be able to present nice insightful visualization, this would not be possible without the great work and efforts of many contributors. The following 'underwater labour' or unseen contributions are:
        The healthcare institutions (hospitals, long-term care homes and retirement homes) who regularly monitor their monitor staff and patients/residents.
        The programmer and testers of Python and especially the developers matplotlib who develop and test matplotlib and make it better with new releases.
        The web developers who develop the portal "https://open.toronto.ca", and maintain it to be up to date.
        The IT support staff who set up the web server to host the data set every year to be up to date.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/23/2026`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
