### Data collected during the research of citation of external sources in GitHub by Python programmers

Overall was collected 50K links to Python repositories which are stored in the `rep_links_data.csv` file. 
The collected data about citeted external sources from comments of issues and pull requests of each repository are stored in `issue_data.csv` and `pulls_data.csv` files.

For file `issue_data.csv` the link to issue in which comments was citation, domains of citated external sources and date of creation of issue 
are palced in columns `issue_link`, `sources` and `date` respectfully. For the file `pulls_data.csv` the link to pull request in which comments was
citation, domains of citated external sources and date of creation of pull request are placed in columns `pull_link`, `sources` and `date` respectfully.

All data was collected from public repositories and public messages left by users by using GitHub API.
