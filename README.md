# cifar-10.2

Repo contains the datasets prepared and published in "Harder or Different?A Closer Look at Distribution Shift in Dataset Reproduction." 

Structure of files is the same as original CIFAR-10 dataset. Files are a pickled dictionary with keywords b'data' and b'labels' where: 
- b'labels': is an integer value corresponding to the relevant CIFAR-10 classes
- b'data': is a flattened array of pixel values. Array must be re-shaped in order to view image correctly. See included notebook for correct reshaping (32x32)

Also included is a meta file stored as a json object. This file contains meta information: 
- TinyKeyword: Keyword in original Tiny Images dataset
- TinyIndex: Index of picture/file in Tiny Images dataset
- Filepath: Filepath derived from TinyImages meta file
- Engine/Page/IndPage/Indengine/Indoverall: Other meta data - for exact definitions see original Tiny Images dataset
