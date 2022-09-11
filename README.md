# Identify South Resident Killer Whales Calls Using CNN and SNN

#### [Project Status]: Ongoing

## __Project Description__
This is a replication project using the methods in [*Detecting, classifying, and counting blue whale calls with Siamese neural networks*](https://asa.scitation.org/doi/10.1121/10.0004828) by Ming Zhong, Maelle Torterotot, and Trevor Branch et al., where convolutional neural networks(CNN) and Siamese neural networks (SNN) were compared in identifying and classifying calls of four types of blue whales. This project will compare the performances of CNN and SNN on identifying calls of Southern Resident Killer Whales. Part of the codes are adapted from the following github repo https://github.com/microsoft/blue-whale-acoustics.

### **Data**
Data used in this project is collected by [**Orcasound**](https://www.orcasound.net/). Orcasound is a open source project that uses hydrophones to live-stream and archive underwater audio data from Bush Point and Port Townsend, Washington, and the Orcasound Lab on the San Juan Island. Details on Orcasound data can be found at the following repo https://github.com/orcasound/orcadata/wiki.

Aduio data was retrieved in May 2022 via [**AWS CLI**](https://registry.opendata.aws/orcasound/). As Orcasound is actively collecting data, future data may not be reflected in this data cut.

The annotation of the data currently contains binary tags for SRKW calls (no clicks or whistles). The replication is therefore simplified from detecting and classifying four type of calls to detecting one type of calls.

### Components of the project
0. Data Exploration: explore the annotated training and testing data 
1. Make spectrograms: make spectrograms according to the annotations and adding tags (positive vs. negative) to spectrograms.
2. CNN: Training CNN models to identify SRKW calls. 
3. SNN: Training SNN models to identify SRKW calls. 

### Author
> [Zoe Liu](https://github.com/liu-zoe)
