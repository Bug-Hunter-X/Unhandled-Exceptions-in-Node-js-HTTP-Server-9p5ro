# Unhandled Exceptions in Node.js HTTP Server

This repository demonstrates a common error in Node.js applications: the lack of proper error handling in HTTP servers.  The `bug.js` file shows a basic server that is susceptible to crashing without providing useful error messages if an exception occurs during request processing.

The `bugSolution.js` file provides a corrected version with comprehensive error handling, ensuring robustness and informative error logging.