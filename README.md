# 📊 GIRLS JUST WANNA HAVE SOME STATS
FINTA* Workshop at 37c3, Day 4 

## Prepare

* To access the Destatis API, you'll need to [register an account at Genesis-Online](https://www-genesis.destatis.de/genesis/online?Menu=Registrierung). Click on the `Registrieren` button and follow the instructions.

* Duplicate `config/login_example.yaml` file and change name to `config/login.yaml`. Add your Destatis login credentials.

* Install the packages we use here, after setting up a virtual environment if you like. \
`pip install -r requirements.txt`


## Try out

`get_data.ipynb`

## Explore 🚀

You can explore Destatis by searching for an attribute you are interested in, e.g. `geschlecht`, using the [online search function](https://www-genesis.destatis.de/genesis/online). This will show you a overview of tables that contain the variable you searched for. You can use the table ID numbers when interacting with the API.

* The [API handbook](https://www-genesis.destatis.de/genesis/misc/GENESIS-Webservices_Einfuehrung.pdf) will be your friend. 