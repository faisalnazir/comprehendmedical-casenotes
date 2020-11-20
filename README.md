# Example code to Analyse Medical casenotes using Amazon Comprehend and Comprehend Medical
This python example shows how a user can process a directory of text-based case notes using Amazon
Comprehend Medical and Comprehend. The code will process all documents within a directory and run
them through both services. It will then export to CSV all Entities, relationships found in both
services for further analysis. 

# Installation
```bash
pip3 -r install requirenents.txt
```
# Usage
```bash
python3 ./comp-med.py --directory <directory> --bucket <bucket>
```
  
