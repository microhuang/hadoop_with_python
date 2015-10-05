# hadoop_with_python

cat l.txt | python m.py | sort | python r.py

haddop -jar streaming.jar -input l.txt -output output -mapper m.py -reducer r.py -combiner r.py -file m.py -file r.py

haddop -jar streaming.jar -input l.txt -output output -mapper "m.py | srot | r.py" -reducer r.py -file m.py -file r.py
