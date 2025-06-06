# Welcome to NequIP

NequIP is an open-source code for machine learning on atomic systems, in particular E(3)-equivariant interatomic potentials. The framework is built for computational performance, ease of use, and extensibility.

## How to use this documentation

The documentation consists of four main sections:
 - The **[User Guide](../guide/guide.rst)** covers getting started, configuration, training techniques, accelerations, and reference materials.
 - The **[Python API](../api/nequip.rst)** documentation.  Most config files and options in the NequIP framework correspond directly to specific functions or classes in the underlying Python API and the comprehensive set of options and arguments that are available are documented in this section.
 - **[Integrations](../integrations/all.rst)** discusses how to use models from the NequIP framework with other software packages.
 - The **[Developer Guide](../dev/dev.rst)** discusses how to extend and contribute to NequIP.

If you're new to NequIP, we recommend starting with the [Installation Guide](../guide/getting-started/install.md), [Workflow Overview](../guide/getting-started/workflow.md), and [Config File documentation](../guide/configuration/config.md).

There is also a [tutorial notebook](https://colab.research.google.com/github/mir-group/nequip-tutorial/blob/main/NequIP_Tutorial.ipynb) that introduces the NequIP framework. This notebook will run entirely on Google Colab's cloud virtual machine and you will not need to install or run anything locally.

## References & citing

**Any and all use of this software, in whole or in part, should clearly acknowledge and link to this repository.**

If you use this code in your academic work, please cite:

 1. The [preprint describing the NequIP software framework](https://arxiv.org/abs/2504.16068):

    > Chuin Wei Tan, Marc L. Descoteaux, Mit Kotak, Gabriel de Miranda Nascimento, Seán R. Kavanagh, Laura Zichi, Menghang Wang, Aadit Saluja, Yizhong R. Hu, Tess Smidt, Anders Johansson, William C. Witt, Boris Kozinsky, Albert Musaelian. <br/>
    > "High-performance training and inference for deep equivariant interatomic potentials." <br/>
    > https://doi.org/10.48550/arXiv.2504.16068

And also consider citing:

 2. The [original NequIP paper](https://www.nature.com/articles/s41467-022-29939-5)

    > Simon Batzner, Albert Musaelian, Lixin Sun, Mario Geiger, Jonathan P. Mailoa, Mordechai Kornbluth, Nicola Molinari, Tess E. Smidt, and Boris Kozinsky. <br/>
    > "E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials." <br/>
    > Nature communications 13, no. 1 (2022): 2453

 3. The [computational scaling paper](https://dl.acm.org/doi/abs/10.1145/3581784.3627041) that discusses optimized LAMMPS MD

    > Albert Musaelian, Anders Johansson, Simon Batzner, and Boris Kozinsky. <br/>
    > "Scaling the leading accuracy of deep equivariant models to biomolecular simulations of realistic size." <br/>
    > In Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis, pp. 1-12. 2023.

 4. The `e3nn` equivariant neural network package used by NequIP, through its [preprint](https://arxiv.org/abs/2207.09453) and/or [code](https://github.com/e3nn/e3nn)

**Extension packages like [Allegro](https://github.com/mir-group/allegro) have their own additional relevant citations.**

## Community, contact, questions, and contributing

If you find a bug or have a proposal for a feature, please post it in the [Issues](https://github.com/mir-group/nequip/issues).
If you have a self-contained question or other discussion topic, try our [GitHub Discussions](https://github.com/mir-group/nequip/discussions).

Active users and interested developers are invited to join us on the NequIP community chat server, which is hosted on the excellent [Zulip](https://zulip.com/) software.
Zulip is organized a little bit differently than chat software like Slack or Discord that you may be familiar with: please review [their introduction](https://zulip.com/help/introduction-to-topics) before posting.
[Fill out the interest form for the NequIP community here](https://forms.gle/mEuonVCHdsgTtLXy7).

We can also be reached by email at [allegro-nequip@g.harvard.edu](mailto:allegro-nequip@g.harvard.edu).
