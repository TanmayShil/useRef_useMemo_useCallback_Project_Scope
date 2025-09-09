# 🚀 React useRef, useMemo, useCallback Hooks Practice Projects

A collection of React + useEffect practice projects with real-world APIs.
Each mini-project focuses on a specific concept like API fetching, debouncing, pagination, infinite scroll, polling, and device state detection.

---

# 1. Stopwatch / Timer App (⏱ useRef)
Scope:
 - Build a stopwatch with Start, Pause, Reset.
 - Use useRef to store the timer ID (so it doesn’t reset every render).
 - Display elapsed time in HH:MM:SS.

👉 Learn: useRef for intervals & storing values without re-render.

# 2. Expensive Calculation Dashboard (📊 useMemo)
Scope:
 - Show a list of numbers (e.g., from API).
 - Add a button to sort/filter large data.
 - Use useMemo to optimize the expensive calculation (sorting/filtering).

👉 Learn: useMemo to avoid re-calculating on every render.

# 3. Todo List with Optimized Children (📝 useCallback + React.memo)
Scope:
 - Parent has a list of todos.
 - Each todo is a child component.
 - Use React.memo on the todo component so it only re-renders when its own props change.
 - Use useCallback to pass stable onDelete and onToggle functions.

👉 Learn: Prevent unnecessary re-renders with useCallback + React.memo.

# 4. Search with Debounce (⌨️ useCallback)
Scope:
 - Build a search input that fetches results from an API (e.g., JSONPlaceholder).
 - Use useCallback to debounce the input handler (e.g., only fetch after 500ms pause).
 - Pass the search function to a memoized child component.

👉 Learn: Stable function references for performance.

# 5. Image Carousel (🖼 useRef)
Scope:
 - Create an image slider that auto-plays.
 - Use useRef to store the interval for auto-play.
 - Add Next/Previous buttons without restarting the auto-play.
   
👉 Learn: useRef for DOM-like behavior & storing mutable values.

# 6. Large Form Optimizer (📝 useMemo + useCallback)
Scope:
 - Build a form with many fields.
 - Use useMemo for derived data (e.g., calculating total cost based on inputs).
 - Use useCallback for handlers (onChange, onSubmit) so form fields don’t re-render unnecessarily.

👉 Learn: Optimizing forms with stable functions & cached values.

# 7. Chat App Message List (💬 React.memo)
Scope:
 - Display chat messages in a list.
 - Wrap each message component with React.memo.
 - Only re-render the new message, not the entire list.

👉 Learn: Use React.memo for big lists.

---

## 🙋‍♂️ Author

Made with ❤️ by Tanmay Shil
GitHub: [@TanmayShil](https://github.com/TanmayShil)
