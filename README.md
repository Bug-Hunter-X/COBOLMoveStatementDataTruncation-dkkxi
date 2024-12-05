This repository contains a simple COBOL program demonstrating a potential data truncation bug.  The program moves a string literal into a variable with a PIC clause that might be insufficient to hold the complete string. This can lead to truncated output or unexpected behavior.

The `bug.cob` file contains the buggy code, while `bugSolution.cob` demonstrates a corrected version.

This example highlights the importance of carefully defining data lengths in COBOL programs to prevent errors caused by data truncation.