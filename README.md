A backend modulnak innen töltöttem le a:

https://drive.google.com/drive/folders/1pQNZ9snByUOMjvEf7Td8Zg1qvBAVhWZ8

Az rbc.h5-öt

A generált fileok 20 százalékát áttettem validation mappákba, de mivel 100 filenál nem enged meg többet feltölteni egyszerre a github, egyelőre ezeket még nem töltöttem fel.

A config_rbc.json-t futtatom.

# A hibaüzenet:

Fused conv implementation does not support grouped convolutions for now.

Elvileg meg kéne változtatnom a placeholder, amit nem tudok, hogy hol van.



# Megjegyzés:
A legújabb tensorflowal nem működik, mert miért lenne visszafelé kompatibilis?

A futtatás előtt le kellett futtatni a :
pip install tensorflow==1.15.0  

parancsot.


