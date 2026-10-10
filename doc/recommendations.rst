Recommendations
===============

Working With This Script
------------------------

1. Work on the exercises in the given order. You may need some of the results you calculate for comparison.

2. Read each of the exercises completely before you start working, as technical hints may be given at the end of exercises.

3. Any program may crash. Always check your outputs and ensure all calculations ran successfully, 
   providing necessary information, as intended based on your given input.

4. Always make sure to redirect the standard output of a program to an appropriate file by using the output operator ``>`` 
   upon calling the program (e.g., ``./program > output.txt``). Otherwise, you may loose important data, 
   and we will have a harder time identifying potential issues.

Trouble Shooting
----------------

Any program may cause a variety of problems. It is thus helpful to follow a few simple guidelines to understand and resolve any issues:

- *Crap in, crap out...* :math:`\rightarrow` Always check your input (input geometries,file formats, input file, chosen keywords, charge, multiplicity, etc.) before you start a calculation.
- If a calculation stops abnormally, check the output (*e.g.* orca.out, job.last, etc.) and error files first.
- Read your output and error files carefully. Pay special attention to the last lines of failed output files for error messages that hint at what may have caused the problem (e.g., an incorrect keyword specification, or a missing input file).
- If you identified the problem, check the program manual for additional options and troubleshooting, and fix the problem by restart the calculation with corrected input(s).
- If your calculations repeatedly stop abnormally and you have exhausted all other possibilities (e.g., input options), prepare a concise description of the problem and contact one of your tutors. Make sure to provide the input, output and any error files or messages, as appropriate.

Further Reading
---------------

If this is your first time working with Linux or quantum chemistry software, fear not; we still have you covered. You can find additional resources in our quantum chemistry II script and on eCampus:

- eCampus: Module MCh WP12 Theoretical Methods for Condensed Matter :math:`\rightarrow` Introductory Course :math:`\rightarrow` Slides Introductory Course
- `Working on Linux <https://qc2-teaching.readthedocs.io/en/latest/setup-linux.html>`_
- `Introduction to Fortran <https://qc2-teaching.readthedocs.io/en/latest/prog-fortran.html>`_
- `Software Recommendations <https://qc2-teaching.readthedocs.io/en/latest/apps-recommendations.html#software-recommendations>`_