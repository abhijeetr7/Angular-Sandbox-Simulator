# Angular-Sandbox-Simulator

This simulator provides a user-friendly interface for experimenting with Angular component structure. You can paste your HTML, CSS, and TypeScript code into the respective editor panes. The "Run Code" button will render your HTML and apply the CSS in the live preview. The "Simulated Component Interaction" section allows you to manually change input values and observe how your component's display might change, and it will log simulated outputs to the console.

Key Features Implemented:

Code Editors: Separate textarea elements for HTML, TypeScript, and CSS, with a tabbed interface for easy switching.

Live Preview: A dedicated area to render the HTML and apply the CSS, giving you a visual representation.

Simulated Inputs/Outputs: Input fields to mimic @Input() properties and a display area for @Output() events, along with basic logic to simulate changes based on button clicks.

Console Output: A dedicated section to display simulated logs and system messages.

Save and Load Sessions: Functionality to save and load the content of all editors and simulated input values using localStorage, allowing you to persist your work.

Clear All: A button to quickly clear all editor content and stored session data.

Responsive Design: Uses Tailwind CSS to ensure the layout adapts well to different screen sizes.

Important Considerations and Limitations:

No Actual Angular Runtime: This simulator does not include the Angular framework. It cannot compile TypeScript, perform true Angular change detection, dependency injection, or routing. The TypeScript editor is purely for display and editing.

Basic HTML/CSS Rendering: The preview is a direct injection of HTML and CSS. It performs very basic string replacements for {{ }} bindings and adds simple event listeners for (click) to demonstrate the concept, but it doesn't parse or execute complex Angular directives or pipes.

Simulated Interactions: The "Simulated Component Interaction" section allows you to manually change values and see how the HTML might update if real Angular bindings were active. The increment() and emitOutput() functions are very basic JavaScript simulations.

This tool is best used for quickly prototyping component HTML and CSS, and for a conceptual understanding of how inputs and outputs might function, rather than for full-fledged Angular debugging or development.
