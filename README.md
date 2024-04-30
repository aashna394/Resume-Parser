# Resume-Parser
The two pdfs are samples that can be given as input to the resume parser. Onet.txt and job_title_mappings are supporting documents that are required for mapping extracted jobs to a standardized version, like junior software developer --> software developer or senior data analyst --> data scientist.

The Resume parser first extracts the text from the document, returns a summary of each section, then extracts the job titles and maps them to a standarized version using onet. It creates a career trajectory of the person and finally returns links of places that are hiring for that particular job as well as relevant links to the applicant's job history, like college rankings and prior places of work.
