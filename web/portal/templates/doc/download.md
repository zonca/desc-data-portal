## How To Download Data

The [CMB-S4 Data Portal](https://data.cmb-s4.org/) allows anyone to transfer the CMB-S4 released data using Globus.

To get started click Login to authenticate into Globus using your organizational login or existing GlobusID. If needed, create a GlobusID using the "Sign Up" link.

If you want to download files to a local machine (e.g., your laptop), you will need to [set up Globus Personal Connect]({{url_for('render_doc', doc_name='globus_personal')}}) on your local machine first.

Once authenticated with Globus, users may transfer either whole directories or individual files by clicking on Transfer from the Home page.  You will be brought to a page like:

![Transfer](/static/img/transfer.png)

### Download Data

If you wish to download whole directories, select the datasets to download and then click Transfer at the bottom of the page.

If you would prefer to download individual files, click on one of the Datasets and you will see a full listing of the dataset directory.

![File Selection](/static/img/fileselect.png)

Choose your files, and then click Transfer. When finished choosing your files, click Transfer, and you will be taken to a Globus page where you will choose the destination for your download.

![Globus](/static/img/globus.png)

Click on Search in the Collection text box and choose a [Collection](https://docs.globus.org/how-to/get-started/#access_a_collection) as your destination.  You may then select a path on that Collection, optionally create a label for this transfer and then click Submit.  If successful, a transfer submission window will appear:

![TransferStarted](/static/img/success.png)

You may monitor the transfer by clicking Refresh until the portal reports the transfer has successfully completed, or visit [globus.org](https://www.globus.org), login if necessary, and use the [Activity](https://docs.globus.org/how-to/get-started/#confirm_transfer_completion) tab.

