# cewa564

Repository with notebooks and files for CEWA 564

For this course we will do our computing and data analysis in the cloud using cloud instances provided by the [Pangeo project](http://pangeo.io/).

## To get started:

1. Create a github account if you do not already have one
2. Go to https://staging.hydro.pangeo.io (select the `small` instance from the spawner options)
3. Start a terminal in your JupyterHub
4. Clone this repository with `git clone https://github.com/bartnijssen/cewa564.git`
5. Install the SUMMA setup so we can run the model by issuing the following commands:
  * `cd cewa564/summa_setup`
  * `./install_local_setup.sh`
  * `mkdir output`
6. Now run the model by issuing the following command:
  * `summa.exe -m ./file_manager.txt`

If all goes well, then the model should run and end with `FORTRAN STOP: finished simulation successfully`

This is not how we will generally interact with the model. Instead we will be using a python package called `pysumma` to interact with the model simulations.
