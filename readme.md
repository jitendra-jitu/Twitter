
/* Fixed SVG button at the bottom-right */
.fixed-bottom-right-btn {
  position: fixed;
  right: 1.25rem;  /* 5 for Tailwind's right-5 */
  bottom: 5.25rem;  /* 5 for Tailwind's bottom-5 */
  z-index: 9999;  /* Make sure it's above other elements */
  background-color: #02afe3;  /* Tailwind's bg-blue-600 */
  padding: 1rem;  /* Padding of 4 for Tailwind's p-4 */
  border-radius: 9999px;  /* Tailwind's rounded-full */
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);  /* Tailwind's shadow-lg */
  cursor: pointer;  /* Pointer cursor on hover */
  display: block;  /* Ensure block-level display for mobile */
}

/* Ensure the SVG is visible and styled correctly */
.fixed-bottom-right-btn svg {
  width: 2rem;  /* Tailwind's w-10 */
  height: 2rem;  /* Tailwind's h-10 */
  fill: #ffffff;  /* White color for the SVG icon */
}

/* Hide on medium and above screens */
@media (min-width: 768px) {
  .fixed-bottom-right-btn {
      display: none;
  }
}


body {
  font-family: TwitterChirp, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  background-color: black;
  color: white;
  cursor: pointer;
}

.custom-scrollbar::-webkit-scrollbar {
  display: none; /* Hide scrollbar in WebKit browsers */
}
.custom-scrollbar {
  -ms-overflow-style: none; /* Hide scrollbar in IE and Edge */
  scrollbar-width: none; /* Hide scrollbar in Firefox */
}

html, body {
  overflow: visible !important;
}