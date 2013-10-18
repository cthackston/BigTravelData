# BigTravelData

Welcome to the Big Travel Data hackathon!


## Getting the SSH private key

In order to access the servers, you'll need to get the SSH keys. [Download it](http://10.101.49.148/hackreduce.pem) with curl:

    $ curl -o ~/.ssh/hackreduce.pem -O http://10.101.49.148/hackreduce.pem
    $ chmod 600 ~/.ssh/hackreduce.pem

Now you can access the servers with the following command:

    $ ssh -i ~/.ssh/hackreduce.pem hackreduce@server


## Accessing the datasets from the clusters

Every node has access to the datasets from the following directories:

    /mnt/hack_data_01
    /mnt/hack_data_02

These directories are read only. A scratch space is available under the following directory:

    /mnt/teams

This is a globally writable directory, so be careful not to overwrite your competitor's data!

## Accessing the datasets from within HackReduce

While you're here at the HackReduce space, you can download the dataset files from the following server:

#### <http://10.101.49.148/>

Download them if you want/need to work with the data from your laptop.
