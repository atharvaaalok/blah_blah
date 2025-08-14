# blah_blah
adfadsf


- [Deep Learning in Fluid Dynamics][DL_in_FD_kutz]
  - 2017
  - Jose N. Kutz
  - [JFM Focus on Fluids][JFM_focus_on_fluids] article for
      [this paper by Ling et al.][Ling_et_al_JFM].
  - Juxtaposes dimensionality reduction techniques like POD, DMD with deep neural networks.
    Focuses light on the work of [Ling et al.][Ling_et_al_JFM], the first to use a truly deep neural
    network and network embedded Galilean invariance for turbulence modeling.
  <details>
  <summary>Main Takeaways</summary>

  - Data methods for fluids have mainly focussed on dimensionality reduction with methods like
    POD, DMD etc.  
    Pros:
    - Dimensionality reduction providing gains in compute and memory.
    - Physically interpretable features.  
    Cons:
    - Cannot capture transient and multi-scale phenomenon.
    - Cannot capture invariances like translation, rotation, scaling.
    
  - Deep neural networks are almost opposite.

    Pros:
    - Can capture multi-scale phenomenon.
    - Can capture invariances.
    
    Cons:
    - High compute demands for training.
    - Not physically interpretable.
    
  - [Ling et al.][Ling_et_al_JFM] use deep neural networks for improved representation of
    Reynolds stress anisotropy tensor. Their approach is novel for:
    - First truly deep neural network (8-10 layers).
    - Embedded Galilean invariance into the network predictions.
    
  </details>

  [DL_in_FD_kutz]: https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/deep-learning-in-fluid-dynamics/F2EDDAB89563DE5157FC4B8342AD9C70
  [JFM_focus_on_fluids]: https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/focus-on-fluids
  [Ling_et_al_JFM]: https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/reynolds-averaged-turbulence-modelling-using-deep-neural-networks-with-embedded-invariance/0B280EEE89C74A7BF651C422F8FBD1EB
