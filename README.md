# Pydata: Pandas Template

## Installation
Includes a `requirements.txt` file to help you to install pandas and its dependencies easily. !Note, you must install `numpy` first as it is an installation dependency that `pip install -r` cannot handle, [see this](http://stackoverflow.com/a/11015904/1445241):

    cd ../
    virtualenv pandas-env
    source pandas-env/bin/activate
    cd pandas-template/
    pip install numpy
    pip install -r requirements.txt

Note: you /may/ get a GCC error installing Bottleneck, this is an unnecessary dependency to get up and running, so consult the [installation documentation](http://pandas.pydata.org/pandas-docs/stable/install.html#dependencies)

## Workshop Samples
Includes samples and tests from this [PyData Pandas workshop](http://www.meetup.com/San-Francisco-PyData/events/113481092/)

