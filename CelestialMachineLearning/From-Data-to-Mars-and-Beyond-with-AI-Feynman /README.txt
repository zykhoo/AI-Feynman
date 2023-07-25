Four jupyter notebooks for the four experiments in our paper.

The first algorithm directly applies AI Feynman with no further biases.

The second algorithm is observationally biased. AI Feynman is informed of the periodicity of Mars' orbit and the trigonometric nature of the data by replacing angular values with their sine and cosine.

The third algorithm is inductively biased. AI Feynman is informed of the periodicity of Mars' orbit and the trigonometric nature of the data by the restriction of the search space. This inference stems from the knowledge that exponential and logarithmic functions only transform dimensionless quantities, therefore cannot transform data representing physical quantities. The inductive bias limits the search space to trigonometric, polynomial and radical functions.

The fourth algorithm combines both observational and inductive biases. AI Feynman is informed of the periodicity of Mars' orbit and the trigonometric nature of the data by both replacing values with their sine and cosine and restricting the search space to trigonometric, polynomial and radical functions.

We conduct four experiments corresponding to the application of the four algorithms, respectively.
