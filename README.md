To run the SKNet and CNN models associated with this report, ensure that your file
structure is properly configured in a high-performance computing (HPC) environment (e.g.,
Rivanna). An acceptable file structure is shown in Figure 9 in Appendix B.

Note that we utilize the PyTorch 2.0.1 kernel on Rivanna while running the code. It is
critical to use a kernel that supports the libraries shown in the first code cell in Figure 9 in Appendix B.

The documentation provided in SKNet.ipynb and CNNBasic.ipynb serves as a guide for
users to understand what a particular cell does and how it is used in the modeling framework.

It is recommended to run the individual cells consecutively such that the libraries and data
will load properly. Note that running the SKNet and CNN models takes several minutes of
processing time. Performance metrics are written to .csv files in the same file path pictured
in Figure 9 in Appensix B.

To run the code within JupyterLab on the Rivanna cluster, it is recommended to configure
a session with the computing options shown in the table below.

Configuration Value
Rivanna partition GPU
Number of hours: 12
Number of cores: 8
Memory request in GB: 100
Work directory: SCRATCH
GPU type for GPU partition default
Number of GPUs: 2

Please contact the authors if any issues arise from attempting to run the code from this
report.