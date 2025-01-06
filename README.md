This repository contains a simple Haskell program demonstrating a common error: Non-exhaustive patterns in function definitions. The bug.hs file shows the erroneous code, and the bugSolution.hs file provides a corrected version.  The error arises from failing to account for all possible cases in a pattern match, specifically the empty list case in this instance. This can lead to runtime exceptions. The solution involves adding a pattern to handle the empty list case, ensuring the function behaves correctly for all valid inputs.