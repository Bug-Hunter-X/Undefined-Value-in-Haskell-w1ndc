# Haskell Undefined Value Bug
This repository demonstrates a common error in Haskell: using an undefined value in a computation. The `bug.hs` file contains the buggy code, which attempts to add 1 to an undefined value. This results in a runtime exception.  The `bugSolution.hs` file provides a corrected version.

This example highlights the importance of handling potential undefined values in Haskell using techniques like pattern matching, maybe monad, or explicit checks for undefined values.