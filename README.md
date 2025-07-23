# Calculator-app

Inspired by the calculator app developed as part of FNB App Academy 2025 course hosted by ITVarsity, this calculator app extends the original by supporting multiple chained operations and continuous calculations after pressing equals—without requiring a reset. It also improves handling of special cases like Infinity and NaN for clearer results. The app’s responsive design ensures it works smoothly across various screen sizes, maintaining usability on both desktop and mobile devices.

Improvements Over the FNB Course Version
The original version covered in the course introduced basic calculator functionality, but it had several limitations:
❌ Could only perform operations on two numbers at a time
❌ Required the user to press AC (All Clear) before starting a new calculation after pressing =
❌ Failed to handle special numeric cases like Infinity or NaN correctly

This version addresses those issues and adds improved logic and usability features:

✅ Chained Operations Support: You can now continuously perform calculations like 5 + 3 * 2 - 4 without resetting after each =.
✅ Post-Equals Continuity: You no longer have to press AC after using = — the result is retained for further operations.
✅ Infinity Handling: The calculator now recognizes and properly displays "Infinity" when dividing by zero or computing infinite results.
✅ NaN Handling: Invalid operations (like 0/0) are detected and displayed as "Undefined" instead of breaking the UI.
✅ Cleaner UX: Improved logic and error handling ensure a smoother experience and more predictable results.
