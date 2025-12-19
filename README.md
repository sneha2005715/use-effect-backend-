🔹 useEffect Hook

useEffect React ka hook hai jo side effects handle karne ke liye use hota hai, jaise:

API calls

Conditional logic

Alerts

DOM ke update ke baad actions

📌 Usage in this Project
Is project me useEffect ka use count state change hone par check karne ke liye kiya gaya hai.

Jab bhi count update hota hai, effect run hota hai

Agar count 3 se divisible hota hai, ek alert show hota hai

Effect sirf count change hone par hi run hota hai (dependency array ke through)

✅ Key Points

Dependency array [count] ensure karta hai ki effect sirf count change hone par chale

Initial render par alert avoid kiya gaya hai

Performance optimized hai (unnecessary renders nahi hote)
