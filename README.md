# Generating-Face-Pictures
Generating Faces using Generative Adversarial Networks
---------------------------------------------------------

**Project motivation:** Training DCGAC netwrok to generate realistic pictures of faces. The concept tis that you have two networks, classifier and generator.
The classifier is normal CNN with output of 1 or 0 (Real or Fake picture). The ganarator is traposed CNN where it takes vector and transfere it to matrix of pixels.

The classifier will be fed real picthures for faces of different celebrity and mark them as real (assigned output of 1), and will recieve and input from the gneenrator, which will start by producing random pictures and will recieve an output of fake (assigned zero for fake images).

As the both networks enhnacing their accuracy (classifier destiguishing real from fake images & generator creating better fake images that are close to real), we reach to a point where images produced by the generator are almost real that the classifier will give it an output of 0.5 (50% chance of being real).

----------------------------------------------------------

**Requirements:**
The following libraries are included:
* numpy
* torch
* helper
* Unittest
* collections
* pickle
* matplotlib

----------------------------------------------------------

**Files in the repository:**
* [dlnd_face_generation.ipynb]: containes the full code
* [dlnd_face_generation HTML]: Code viewed from browser
* [problem_unittests]:To test pieces of codes written in dlnd_face_generation.ipynb

*data used:* it was provided by Udacity

-----------------------------------------------------------------

**Results:**
You can find a summary of my result either at the presentation, report, of my blog post.

-------------------------------------------------------------------

**Acknowledgement:**
This project was built over the data availed from Udacity.


