Pentabarf XML to RDF Converter
==============================

I wrote this script during the [linked data workshop at Chaos Communication Camp
2011](https://events.ccc.de/camp/2011/wiki/LinkedData). It converts Pentabarf
Schedule XML files to RDF using Python RDFLib. Where possible, i adhere to [Dan
Hagon's Fahrplan ontology](https://github.com/axiomsofchoice/CCC2011_LOD_workshop/blob/master/schedule.owl). 
It doesn't contain all properties I use... I'll probably extend it later.


Usage:
------

- Download a schedule file and run:

    ./convert.py example_schedule.xml
- Error message of the code: 
```AssertionError: Term http://events.ccc.de/camp/2011/wiki/Call_for_Space_Program must be an rdflib term```

**Output**
------
Visualization with GATE Ontology Viewer
----
<img src="https://github.com/susierao/pentabarf-rdf/blob/susierao-patch-1/gate_vis.PNG" alt="vis"/>
