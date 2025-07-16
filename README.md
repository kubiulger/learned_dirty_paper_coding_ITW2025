# learned_dirty_paper_coding_ITW2025


## Abstract

Dirty paper coding (DPC) is a classical problem in information theory that considers communication in the presence of channel state known only at the transmitter. While the theoretical impact of DPC has been substantial, practical realizations of DPC, such as Tomlinson–Harashima precoding (THP) or lattice-based schemes, often rely on specific modeling assumptions about the input, state and channel. In this work, we explore whether modern learning-based approaches can offer a complementary path forward by revisiting the DPC problem. We propose a data-driven solution in which both the encoder and decoder are parameterized by neural networks. Our proposed model operates without prior knowledge of the state (also referred to as ``interference''), channel or input statistics, and recovers nonlinear mappings that yield effective interference pre-cancellation. To the best of our knowledge, this is the first interpretable proof-of-concept demonstrating that learning-based DPC schemes can recover characteristic features of well-established solutions, such as THP and lattice-based precoding, and outperform them in several regimes.
