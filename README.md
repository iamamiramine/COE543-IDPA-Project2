# COE543-IDPA-Project2
Data Processing Algorithms: Vector Space Model

Libraries needed to run this project:

  1-numpy

  2-xml

  3-lxml

  4-tkinter
  
  5-scikit-learn
  
This project combines the Tree Edit Distance algorithm (provided in https://github.com/iamamiramine/COE543-IDPA-Project1) to compare it with Vector Space Model. The comparison is based on speed and accuracy of both algorithms trying to find the similarities between two XML documents. Additionaly, using VSM, we developed an elastic search engine that ranks most similar documents based on a search query, using techniques to improve precision and recall of the model such as indexing.

The gui.py script runs the whole project through a graphical user interface

In the ./TED folder, the python scripts provide the same functionality as in https://github.com/iamamiramine/COE543-IDPA-Project1. Additionally, the simTED.py script in the same folder returns the similarities between two XML documents based on N&J Tree Edit Distance Algorithm

In the ./VSM folder:

    1-preprocessing.py computes the TF and IDF weights of the documents inside the ./DocumentsDB folder which includes a set of XML documents by taking into consideration the structure of the XML document only and the structure and content of the XML document. docsProc.py script runs the preprocessing.py script on the dataset of XML documents.
    
    2-

