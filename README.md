This is the initial POC of an NLP dedicated to categorizing and flagging sexual harassment messages.

This program is dedicated to the initiative of Samantha Unrau with a shout out as well to Candice Christiansen.

I am going to be using a local installation of the spaCy library (spacy.io) or GPT-3, depending on use case approval, to set this up. To download the same configuration that I will be using you can use something like what is modeled on the spaCy download page:

python3 -m venv .env

source .env/bin/activate

pip install -U pip setuptools wheel

pip install -U 'spacy[transformers,lookups,apple]'

python3 -m spacy download en_core_web_sm




I am not super well versed in branching on Git at this point so any help with this is appreciated. I will be pushing my updates to individual branches depending on the criteria that I update and merging these over time with the master branch.

Please spread this far and wide. The eventual goal in this will be an API that can be set up to filter content through for various online social platforms to report and catalogue sexual harassment.
