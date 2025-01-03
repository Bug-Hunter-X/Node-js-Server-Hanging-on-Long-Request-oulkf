# Node.js Server Hanging on Long Request

This repository demonstrates a common issue in Node.js where a long-running request in a synchronous manner blocks the event loop, causing the server to appear unresponsive to other requests. The `bug.js` file contains the problematic code. The `bugSolution.js` demonstrates a solution using asynchronous operations.