# Ziffernerkennung mit PYthon und DyNet

In diesem Archiv finden Sie ein Beispiel für die Ziffernunterscheidung mithilfe 
eines sehr einfachen neuronalen Netzes (sowie einiger Varianten desselben).

Das Beispiel liegt in zwei Formen vor: 

1. als Python-Skript (mnist-autobatch.py), 
2. als Jupyter-Notebook (mnist.ipynb). 

Für beide Varianten ist es erforderlich, dass Sie [DyNet](https://github.com/clab/dynet/) installieren. 
Eine Anleitung dafür finden Sie unter https://dynet.readthedocs.io/en/latest/python.html . 
Bei Problemen melden Sie sich gerne im Forum, möglichst mit einer detaillierten Beschreibung Ihres Setups und an welcher Stelle Sie scheitern.

Sie können nun das Python-Skript mit `python3 ./mnist-autobatch.py` aufrufen (oder, noch besser, über eine IDE wie PyCharm). 

Alternativ (oder zusätzlich) können Sie Jupyter auf Ihrem Computer installieren und das inhaltlich identische Jupyter Notebook ausführen. 
(Der Vorteil dabei ist, dass Sie interaktiv Dinge ändern und einzelne Code-Abschnitte erneut ausführen können.)

Schließlich können Sie das Jupyter-Notebook auch online auf mybinder.org ausführen. Sie können dann zwar den Code auch abändern und neu ausführen (wie in jedem Jupyter Notebook), 
aber Sie können Ihre Ergebnisse leider nicht dauerhaft abspeichern.
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/timobaumann/mnist-example/master)
