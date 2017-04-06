Polecam skorzystanie z dockera: https://hub.docker.com/r/cannin/jupyter-keras-tensorflow-tools/

Wart by maszyna wirtualna Dockera miała tak z 12Gb pamięci i kilka procesorów, inaczej pojawią się problemy.

W przypadku prezentacji deep learning odpalamy w pierwszej komórce Jupyter Notebooka (przed całym kodem):

!pip install --upgrade keras tensorflow
!apt-get update
!apt-get install graphviz -y
!pip install pydot-ng

W przypadku prezentacji machine learning:

!pip install --upgrade xgboost keras tensorflow seaborn imblearn
!apt-get install python-tk -y


Ewentualnie wystarczy na maszynę Dockera wrzucić plik config.sh i odpalić go z konsoli na maszynie:
bash config.sh 
Zostaną wtedy doinstalowane wszystkie potrzebne pakiety :).
Powodzenia!



