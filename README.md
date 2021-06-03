## SIP Project AST-07: Using the Canada-France-Hawaii Legacy Survey to Study Distant RR Lyrae Stars in the Halo of the Milky Way Galaxy

Current Jupyter notebook code works with files extracted from the "full" Deep Field stellar photometric timeseries data [here](https://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/en/megapipe/cfhtls/dfspt.html).
The `tar.gz` file needs to be extracted into the working directory, ie. `working-directory/full` will contain the data. 
To work with the exposure numbers and exposure times, download all the `.list` files under Deep Fields (full) [here](https://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/en/megapipe/cfhtls/input.html).
Then, create a new directory called `fields` in the working directory and move the `.list` files there, ie. the exposure data should be at `working-directory/fields/*.list`.

Of course, you can change the file paths in the Jupyter notebook for your own computer, and there should be annotations in the notebook indicating where you would do so.

I did not upload images/figures or additional files created in the process of running the Jupyter notebook in the repository. 
Most of the figures are presented within the notebook itself, and files can be saved locally by just uncommenting any `plt.savefig()` or `np.savetxt()` commands.

To just view the Jupyter notebook, you can use [nbviewer](https://nbviewer.jupyter.org/).

In part of this project, SAOImageDS9 was used to view the CFHTLS images. Further details on how and why can be found in the Jupyter notebook annotations.
You can download DS9 [here](https://sites.google.com/cfa.harvard.edu/saoimageds9) and the CFHTLS images are available [here](https://www.cadc-ccda.hia-iha.nrc-cnrc.gc.ca/en/megapipe/cfhtls/scrollD2.html)