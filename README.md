you will need:

python 2.7
numpy
ScientifcPython
Numeric python (will be deprecated in future releases)

you may need:

libatlas*
netcdfg*
gfortran

  can use sudo apt-get install "name as above" to get these.
    if on windows the name may be different

if struggling to build from source (pathing is a bitch with python-C) do what I did:

 sudo apt-get install libatlas*
 sudo apt-get install netcdfg*
 sudo apt-get install gfortran
 sudo apt-get install python-pip python-dev build-essential
 sudo pip install scipy
 sudo pip install ScientificPython
 wget https://sourcesup.cru.fr/frs/download.php/3794/MMTK-2.7.5.tar.gz
 sudo pip install MMTK-2.7.5.tar.gz
