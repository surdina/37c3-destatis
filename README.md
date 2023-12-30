# 📊 GIRLS JUST WANNA HAVE SOME STATS


Welcome to today's workshop! This page will guide you through the Destatis workshop at 37c3, Day 4. 


## Prerequisites
* **This workshop requires beginner programming/data analysis skills**: You should have an editor of your choise set up, and be able to do basic things like read in a csv file.
* The workshop materials use Python 3.

## Preparation steps

### Account registration for API access

* To access the Destatis API, you'll need to registeer an account.
  * Go to [Genesis-Online Registration](https://www-genesis.destatis.de/genesis/online?Menu=Registrierung). 
  * Click `Registrieren` and follow the instructions.

### Repository download

* Clone or download this repository to your local machine.
  * **Git Clone:** Use git clone. Learn how to do this [here](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository).
  * GitHub Download: Go to the GitHub page, click the green "Code" button, then "Download ZIP".
  * If unfamiliar with Git, simply ensure you download and extract the files to your computer.

### Configuration file setup

* Duplicate the `config/login_example.yaml` file.
* Rename the duplicate to `config/login.yaml`.
* Enter your Destatis login credentials in this file.


### Environment and Package Installation

* (Optional) Set up a virtual environment for package management.
* Install required packages using pip:
Run `pip install -r requirements.txt` in your terminal or command prompt.




## Try out the notebook

* Notebook Name: `get_data.ipynb`
* Open and run the notebook to try out the workshop material. This notebook is designed to guide you through the process of fetching data using the API.



## Explore with Destatis 🚀
### Discover data attributes

* Use the [Destatis Online Search](https://www-genesis.destatis.de/genesis/online) to look for specific attributes, like `geschlecht`.
  * You can get lists of tables directly from the notebook, but the website is more user-friendly for getting an overview.
  * This search will provide an overview of tables containing the searched variable. Note down the table ID numbers for API interactions.

* The [API handbook](https://www-genesis.destatis.de/genesis/misc/GENESIS-Webservices_Einfuehrung.pdf) will be your friend. 

## Explore 🚀

You can explore Destatis by searching for an attribute you are interested in, e.g. `geschlecht`, using the . This will show you a overview of tables that contain the variable you searched for. You can use the table ID numbers when interacting with the API.

# Notes

* Compatibility: This code has been tested using Python version `3.10.9`.
* Feedback and Queries: For any questions, clarifications, or feedback regarding the workshop content, feel free to raise your hand! 