
# Masterclass 22.07: Learning and enhancing fluctuations along information bottleneck for automated enhanced sampling

This lesson was given as part of the PLUMED masterclass series in 2022.  It includes:

* Two videos that describe the theory. 
* Two python notebooks that describe what you can do using these methods.

The flow chart shown below indicates the order in which you should consult the resources.  You can click on the nodes to access the various resources.  Follow the thick black lines for the best results.  The resources that are connected by dashed lines are supplmentary resources that you may find useful when completing the exercise.

This lesson was the seventh masterclass in the 2022 series.

```mermaid
flowchart TB;

  A[ref1] ==> C[Lecture I];
  C ==> D[notebook I];
  D ==> E[Lecture II];
  E ==> F[notebook II];
  G[Metadynamics Theory] -.-> C
  C -.-> I
  I[Using PyTorch] -.->D
  B[ref2] -.-> E;
  H[Variational autoencoder Theory] -.-> C
    
  click A "ref1" "The paper about the SPIB method introduced in this tutorial";
  click B "ref2" "A paper that describes how the SPIB method was applied to two biophyically relevant systems";
  click C "video1" "A lecture that was given on May 9th 2022 as part of the plumed masterclass series that introduces you to the exercises in this lesson";
  click D "Tutorial_1_plumed_SPIB_masterclass_2022.ipynb" "A python notebook that describes the exercises that were introdced in the first video";
  click E "video2" "A lecture that was given on May 16th 2022 as part of the plumed masterclass series that goes through the solutions to the exercises in the lesson";
  click F "Tutorial_2_plumed_SPIB_masterclass_2022.ipynb" "A python notebook that includes the exercises that were introduced in the second video";
  click G "ref3" "Brief introduction to Metadynamics as an enhanced sampling technique";
  click H "ref4" "Paper that introduces the Variational autoencoder with VampPrior neural network architechture employed in SPIB";
  click I "ref5" "Brief tutorial that introduces PyTorch to beginners. For improved understanding of SPIB implementation, please explore the tutorials hosted on PyTorch website";
```
