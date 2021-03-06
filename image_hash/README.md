## Near-duplicate image search

**App type**: command line.

**Stack**:
* Numpy
* Pillow

**Main topics**:
* Perceptual image hashing (difference hashing, aka d-hash)
* Command-line argument parsing

**Project source/inspiration**:
Test task from Summer School on Machine Learning by Rails Reactor.

**Project description**:

The task is to develop a console tool which finds similar images in a given folder and prints similar pairs.

There are three types of similarity:
- duplicate (images which are exactly the same)
- modification (images which differ by size, blur level or noise filters)
- similar (images of the same scene from another angle)

The images are marked in the dataset with words in the file names that correspond to the type of similarity. The minimal acceptable solution should be able to find “duplicates”. The complete solution should handle all three types of similarity.
Also, you are only allowed to use plain python with the standard library and the following libraries: https://pillow.readthedocs.io/en/stable/ and https://www.numpy.org/ . You shouldn't use filenames to identify duplicates and be aware that another dataset will be used for assessing solution
performance .
