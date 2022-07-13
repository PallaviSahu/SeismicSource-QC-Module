# SeismicSource-QC-Module
This Module uses tkinter, sqlite libraries
It is GUI dialog that take acquisition log as input.
Acquisition log consist of details of seismic source at field operations, eg Pressure, Volume, GunSeparation, GunDepth, Status, Sequence, Swath, date, source number.. so forth
This module is used to filter the acquisition log according to user inputs and check the shot is good/bad as per contractual limits of Volume, Pressure, GunSeparation, and GunDepth
1) It generates user interative plot showing Volume, Pressure, GunSeparation, Gun Depth Vs Station Number. 2) Output.csv file consist of filtered data as per user inputs. 3) Bad_shots.csv file that consist of analysed badshots.
