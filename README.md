# THIS LIBRARY HAS NOT YET BEEN CREATED

# NexRad-Level-II-Creator
A library to create and edit Level-II Files, as specified in ICDs [2620010H](https://www.roc.noaa.gov/WSR88D/PublicDocs/ICDs/2620010H.pdf) and [2620002W](https://www.roc.noaa.gov/WSR88D/PublicDocs/ICDs/2620002W.pdf).
Inspired by [MetPy]([url](https://github.com/Unidata/MetPy)), this project aims to be able to allow users to manipulate Level-II data. 

## Use case examples: 
- Exporting only low-elevation (tilt) data
- Converting to/from Level-II data
- Making fake radar screenshots for memes

# Usage
This is all in the air. The plan is that the lib will turn a file into a [NamedStruct](https://github.com/hubo1016/namedstruct) that users can interface with. This means users will still need to know the structure of the file and messages from the ICDs, but in exchange, keeps data in a format that can be imported and exported. 

# FAQs:
Q: Why Python? WHY????

A: I am lazy. I started this so I could get GR2 Analyst 3 UDPs to process on every SAILS sweep.

Q: I hate how you are doing this.

A: So do I, and that isn't a question. 

Q: Why are so many things missing? 
A: I haven't done them yet. 

Q: When will you do them?

A: I don't know.

Q: Can I contribute

A: yes please. 


